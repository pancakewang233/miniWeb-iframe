<script setup lang="ts">
import Breadcrumb from './Breadcrumb.vue';
import MainVue from '../views/Main.vue';
import SideBar from './SideBar.vue'
</script>

<template>
  <div class="flex flex-col w-screen h-screen">
    <header class="flex border border-black-500 h-12 justify-center items-center">
      微前端-iframe框架
    </header>
    <main class="flex flex-1">
      <SideBar class="w-60"/>
      <div class="flex flex-col w-full">
        <Breadcrumb class="flex border border-purple-500 pl-4 h-10 items-center" />
        <MainVue />
      </div>
    </main>
  </div>
</template>
