<script>
  export let href;
  export let light = false;
  export let sub = false;
  export let external = false;
  export let lg = false;
  export let white = false;

  const color = light
    ? "text-blue-400 hover:bg-blue-400 border-blue-400 focus:ring-blue-400 focus:ring-offset-gray-900"
    : sub
    ? "text-gray-900 hover:bg-gray-900 border-gray-900 focus:ring-gray-900 focus:ring-offset-white"
    : white
    ? "text-white hover:bg-white border-white focus:ring-white focus:ring-offset-blue-600"
    : "text-blue-600 hover:bg-blue-600 border-blue-600 focus:ring-blue-600 focus:ring-offset-white";

  const size = lg ? "py-3 px-6 text-lg" : "py-2 px-5 text-base";
</script>

<a
  target={external ? "_blank" : "_self"}
  class={`${color} ${size} border hover:scale-110 transition-all hover:bg-opacity-10 active:scale-95 inline-flex items-center justify-center focus:outline-none focus:ring-1 focus:ring-offset-2 text-center`}
  {href}
>
  <slot />
  {#if external}
    <svg
      xmlns="http://www.w3.org/2000/svg"
      class="h-5 w-5 ml-2"
      fill="none"
      viewBox="0 0 24 24"
      stroke="currentColor"
    >
      <path
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2"
        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
      />
    </svg>
  {/if}
</a>
