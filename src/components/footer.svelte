<script>
  import Button from "./button.svelte";
  import Container from "./container.svelte";
</script>

<div class="py-5 border-t">
  <Container>
    <div
      class="flex items-center justify-between flex-col space-y-5 sm:flex-row sm:space-y-0"
    >
      <div
        class="flex items-center space-y-5 flex-col sm:flex-row sm:space-y-0 sm:space-x-5 flex-1"
      >
        <img src="/rk-logo-black.svg" class="h-10" alt="Raymond Kneipp Logo" />

        <div class="flex flex-col items-center sm:items-start">
          <h6 class="font-bold text-base">Raymond Kneipp Web Design</h6>
          <p class="text-sm">Building websites since 2014</p>
        </div>
      </div>

      <div class="items-center space-x-5 flex">
        <a
          href="/raymond-kneipp-resume.pdf"
          rel="external"
          class="text-gray-900 transform hover:scale-125 active:scale-95 transition-all focus:outline-none focus:ring-1 focus:ring-gray-900 focus:ring-offset-2 focus:ring-offset-white p-2"
        >
          <svg
            class="h-6 w-6"
            viewBox="0 0 24 24"
            fill="currentColor"
            xmlns="http://www.w3.org/2000/svg"
            fill-rule="evenodd"
            clip-rule="evenodd"
            ><path
              d="M3 24h19v-23h-1v22h-18v1zm17-24h-18v22h18v-22zm-3 17h-12v1h12v-1zm0-3h-12v1h12v-1zm0-3h-12v1h12v-1zm-7.348-3.863l.948.3c-.145.529-.387.922-.725 1.178-.338.257-.767.385-1.287.385-.643 0-1.171-.22-1.585-.659-.414-.439-.621-1.04-.621-1.802 0-.806.208-1.432.624-1.878.416-.446.963-.669 1.642-.669.592 0 1.073.175 1.443.525.221.207.386.505.496.892l-.968.231c-.057-.251-.177-.449-.358-.594-.182-.146-.403-.218-.663-.218-.359 0-.65.129-.874.386-.223.258-.335.675-.335 1.252 0 .613.11 1.049.331 1.308.22.26.506.39.858.39.26 0 .484-.082.671-.248.187-.165.322-.425.403-.779zm3.023 1.78l-1.731-4.842h1.06l1.226 3.584 1.186-3.584h1.037l-1.734 4.842h-1.044z"
            /></svg
          >
        </a>
        <a
          href="https://www.linkedin.com/in/raymondkneipp/"
          class="text-gray-900 transform hover:scale-125 active:scale-95 transition-all focus:outline-none focus:ring-1 focus:ring-gray-900 focus:ring-offset-2 focus:ring-offset-white p-2"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            viewBox="0 0 24 24"
            fill="currentColor"
            ><path
              d="M0 0v24h24v-24h-24zm8 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.397-2.586 7-2.777 7 2.476v6.759z"
            /></svg
          >
        </a>
        <a
          href="https://github.com/raymondkneipp"
          class="text-gray-900 transform hover:scale-125 active:scale-95 transition-all focus:outline-none focus:ring-1 focus:ring-gray-900 focus:ring-offset-2 focus:ring-offset-white p-2"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            viewBox="0 0 24 24"
            fill="currentColor"
            ><path
              d="M0 0v24h24v-24h-24zm14.534 19.59c-.406.078-.534-.171-.534-.384v-2.195c0-.747-.262-1.233-.55-1.481 1.782-.198 3.654-.875 3.654-3.947 0-.874-.311-1.588-.824-2.147.083-.202.357-1.016-.079-2.117 0 0-.671-.215-2.198.82-.639-.18-1.323-.267-2.003-.271-.68.003-1.364.091-2.003.269-1.528-1.035-2.2-.82-2.2-.82-.434 1.102-.16 1.915-.077 2.118-.512.56-.824 1.273-.824 2.147 0 3.064 1.867 3.751 3.645 3.954-.229.2-.436.552-.508 1.07-.457.204-1.614.557-2.328-.666 0 0-.423-.768-1.227-.825 0 0-.78-.01-.055.487 0 0 .525.246.889 1.17 0 0 .463 1.428 2.688.944v1.489c0 .211-.129.459-.528.385-3.18-1.057-5.472-4.056-5.472-7.59 0-4.419 3.582-8 8-8s8 3.581 8 8c0 3.533-2.289 6.531-5.466 7.59z"
            /></svg
          >
        </a>
      </div>
    </div>
  </Container>
</div>
