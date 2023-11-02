<template>
  <div class="max-w-7xl mx-auto grid grid-cols-4 gap-4">
    <div class="main-left col-span-3 space-y-4">
      <div class="bg-white border border-gray-200 rounded-lg">
        <div class="p-4 flex space-x-4">
          <input
            type="search"
            class="p-4 w-full bg-gray-100 rounded lg"
            placeholder="Search terms ..."
          />
          <a
            href="#"
            class="inline-block py-4 px-6 bg-purple-600 text-white rounded-lg"
            >Post</a
          >
        </div>
      </div>
      <!-- Search Result -->
      <div
        class="p-4 bg-white border border-gray-200 rounded-lg grid grid-cols-4 gap-4"
      >
        <div class="p-4 text-center bg-gray-100 rounded-lg">
          <img src="placeholder.jpg" alt="" class="mb-6 rounded-full" />
          <p><strong>Code With Stein</strong></p>
          <div class="mt-6 flex space-x-8 justify-around">
            <p class="text-xs text-gray-500">182 friends</p>
            <p class="text-xs text-gray-500">120 posts</p>
          </div>
        </div>
      </div>
    </div>
    <!-- Right Col -->
    <div class="main-right col-span-1">Right</div>
  </div>
</template>
