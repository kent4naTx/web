<script></script>
<template>
  <!-- BANNER DE FATO-->
  <div
    class="relative pt-16 pb-32 flex content-center items-center justify-center"
    style="min-height: 75vh"
  >
    <div
      class="absolute top-0 w-full h-full bg-center bg-cover"
      style="
        background-image: url('https://images2.alphacoders.com/103/103282.jpg');
      "
    >
      <span
        id="blackOverlay"
        class="w-full h-full absolute opacity-75 bg-black"
      ></span>
    </div>
    <div class="container relative mx-auto">
      <div class="items-center flex flex-wrap">
        <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
          <div class="pr-12">
            <h1 class="text-white font-semibold text-5xl uppercase">
              {{ $t("calling-banner") }}
            </h1>
            <p class="mt-4 text-lg text-gray-400">
              {{ $t("text-banner") }}
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- BANNER DE FATO-->

    <!-- PARTE QUE DA O FORMATO DA IMAGEM -->
    <div
      class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
      style="height: 70px"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon
          class="text-gray-200 fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>
    <!-- PARTE QUE DA O FORMATO DA IMAGEM -->
  </div>
</template>
