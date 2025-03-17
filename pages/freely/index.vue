<template>
  <main class="container mx-auto p-4">
    <!-- <div class="bg-gray-500 h-16 w-16 aspect-[1/5]"></div> -->
    <!-- <img class="mx-auto aspect-[1/5]" src="https://placehold.co/600x400" /> -->

    <!-- <div
      class="flex flex-col gap-2 p-8 sm:flex-row sm:items-center sm:gap-6 sm:py-4 border-2 border-gray-200 rounded-lg justify-center max-w-sm mx-auto"
    >
      <img
        class="mx-auto block h-24 rounded-full sm:mx-0 sm:shrink-0"
        src="https://placehold.co/600x400"
        alt=""
      />
      <div class="space-y-2 text-center sm:text-left">
        <div class="space-y-0.5">
          <p class="text-lg font-semibold text-black">Erin Lindford</p>
          <p class="font-medium text-gray-500">Product Engineer</p>
        </div>
        <button
          class="border-purple-200 text-purple-600 hover:border-transparent hover:bg-purple-600 hover:text-white active:bg-purple-700 ..."
        >
          Message
        </button>
      </div>
    </div> -->

    <p class="text-2xl font-bold my-4">Columns</p>
    <div class="columns-1 sm:columns-2 md:columns-3 xl:columns-5 gap-4">
      <div class="bg-blue-200 p-4 mb-4 rounded">항목 1</div>
      <div class="bg-blue-300 p-4 mb-4 rounded">항목 2</div>
      <div class="bg-blue-400 p-4 mb-4 rounded">항목 3</div>
      <div class="bg-blue-500 p-4 mb-4 rounded">항목 4</div>
      <div class="bg-blue-600 p-4 mb-4 rounded">항목 5</div>
    </div>

    <p class="text-2xl font-bold my-4">Grids</p>

    <div class="grid grid-cols-3 gap-4">
      <div class="bg-blue-200 p-4 rounded">항목 1</div>
      <div class="bg-blue-300 p-4 rounded">항목 2</div>
      <div class="bg-blue-400 p-4 rounded">항목 3</div>
      <div class="bg-blue-500 p-4 rounded">항목 4</div>
    </div>

    <p class="text-2xl font-bold my-4">break-after1</p>
    <div class="columns-2 gap-4">
      <p class="bg-gray-100 p-2">첫 번째 단락: 이건 그냥 흘러가요.</p>
      <p class="bg-gray-200 p-2 break-after-column">두 번째 단락: 여기서 컬럼이 끊겨요!</p>
      <p class="bg-gray-300 p-2">세 번째 단락: 다음 컬럼에서 시작.</p>
      <p class="bg-gray-400 p-2">네 번째 단락: 이어서 진행.</p>
    </div>

    <p class="text-2xl font-bold my-4">break-after2</p>

    <div class="columns-2 gap-4">
      <p class="bg-blue-100 p-2">첫 번째 단락: 길게 써도 괜찮아요.</p>
      <p class="bg-blue-200 p-2 break-after-avoid">
        두 번째 단락: 이건 끊기면 안 돼요!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
      </p>
      <p class="bg-blue-300 p-2">세 번째 단락: 이어서 진행.</p>
    </div>

    <p class="text-2xl font-bold my-4">예제 1: 테두리와 패딩 포함 (box-border)</p>
    <div class="box-border size-32 border-4 p-4 bg-blue-200">콘텐츠</div>
    <p class="text-2xl font-bold my-4">예제 2: 테두리와 패딩 제외 (box-content)</p>
    <div class="box-content size-32 border-4 p-4 bg-green-200">콘텐츠</div>

    <p>
      오늘은
      <span class="inline-flex items-center gap-2 bg-green-100">
        <span class="bg-green-200 p-1">항목 1</span>
        <span class="bg-green-300 p-1">항목 2</span> </span
      >에 대해 배웠어요.
    </p>
    <div class="grid grid-cols-3 gap-4 bg-gray-200 p-4">
      <div class="bg-red-200 p-2">1</div>
      <div class="bg-red-300 p-2">2</div>
      <div class="bg-red-400 p-2">3</div>
      <div class="bg-red-500 p-2">4</div>
    </div>
    <div class="flex gap-2 bg-purple-100 p-4">
      <div class="bg-purple-200 p-2">1</div>
      <div class="contents">
        <div class="bg-purple-300 p-2">2</div>
        <div class="bg-purple-400 p-2">3</div>
      </div>
      <div class="bg-purple-500 p-2">4</div>
    </div>
  </main>
</template>

<script lang="ts" setup></script>

<style></style>
