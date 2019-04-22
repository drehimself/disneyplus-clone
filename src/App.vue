<template>
  <div id="app" class="flex bg-gray-900 text-white min-h-screen">
    <sidebar-navigation />

    <div class="w-full">
      <transition name="page" mode="out-in">
        <router-view/>
      </transition>
    </div>
  </div>
</template>

<script>
import SidebarNavigation from '@/components/SidebarNavigation'

export default {
  components: {
    SidebarNavigation
  }
}
</script>


<style src="./css/main.css">
