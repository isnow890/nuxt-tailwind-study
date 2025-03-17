<template>
  <div>
    <header class="bg-gray-100 p-6 rounded-lg mb-6">
      <nav class="flex justify-between items-center">
        <!-- 좌측: 로고 -->
        <div class="text-2xl font-bold">MyWebsite</div>

        <!-- 중앙: 네비게이션 링크 -->
        <ul class="flex gap-4">
          <li>
            <a href="#" class="text-gray-700 hover:text-gray-900">Home</a>
          </li>
          <li>
            <a href="#" class="text-gray-700 hover:text-gray-900">About</a>
          </li>
          <li>
            <a href="#" class="text-gray-700 hover:text-gray-900">Services</a>
          </li>
          <li>
            <a href="#" class="text-gray-700 hover:text-gray-900">Contact</a>
          </li>
        </ul>

        <!-- 우측: 로그인 버튼 -->
        <div>
          <button class="bg-blue-500 text-white py-2 px-4 rounded hover:bg-blue-700" type="button">
            Login
          </button>
        </div>
      </nav>
    </header>

    <header>
      <nav class="p-5 bg-gray-100 flex justify-between items-center">
        <div class="text-2xl font-bold">MyWebsite</div>

        <ul class="flex gap-5 text-gray-600">
          <li class="hover:text-indigo-600 cursor-pointer">Home</li>
          <li>About</li>
          <li>Service</li>
          <li>Contact</li>
        </ul>
        <button class="bg-blue-500 py-2 px-4 text-white rounded hover:bg-blue-700">Login</button>
      </nav>
    </header>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
