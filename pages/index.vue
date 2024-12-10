<!--
* @Component: 
* @Maintainer: J.K. Yang
* @Description: 
-->
<script setup lang="ts"></script>

<template>
  <div class="p-5">
    <div
      class="max-w-sm rounded-lg overflow-hidden shadow-lg bg-white hover:shadow-xl transition-shadow duration-300"
    >
      <!-- 角色图片 -->
      <img
        class="w-full h-48 object-cover"
        src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=388&auto=format&fit=crop"
        alt="角色头像"
      />

      <!-- 卡片内容 -->
      <div class="px-6 py-4">
        <div class="flex items-center justify-between mb-2">
          <h3 class="font-bold text-xl text-gray-800">Sarah Johnson</h3>
          <span class="inline-block bg-blue-500 rounded-full w-3 h-3"></span>
        </div>

        <p class="text-gray-600 text-sm mb-4">产品设计师 / UX设计师</p>

        <!-- 角色标签 -->
        <div class="flex gap-2 mb-4">
          <span
            class="px-3 py-1 text-xs font-semibold text-blue-600 bg-blue-100 rounded-full"
          >
            设计
          </span>
          <span
            class="px-3 py-1 text-xs font-semibold text-green-600 bg-green-100 rounded-full"
          >
            产品
          </span>
        </div>

        <!-- 角色信息 -->
        <div class="space-y-2 text-sm text-gray-600">
          <div class="flex items-center gap-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-4 w-4"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
              />
            </svg>
            <span>sarah.johnson@example.com</span>
          </div>
          <div class="flex items-center gap-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-4 w-4"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
              />
            </svg>
            <span>+1 234 567 890</span>
          </div>
        </div>
      </div>

      <!-- 卡片底部 -->
      <div class="px-6 py-4 bg-gray-50 border-t border-gray-100">
        <div class="flex justify-between items-center">
          <div class="flex items-center gap-2">
            <span class="w-2 h-2 bg-green-500 rounded-full"></span>
            <span class="text-sm text-gray-600">在线</span>
          </div>
          <button
            class="px-4 py-2 bg-blue-500 text-white text-sm font-medium rounded-md hover:bg-blue-600 transition-colors duration-300"
          >
            查看详情
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss"></style>
