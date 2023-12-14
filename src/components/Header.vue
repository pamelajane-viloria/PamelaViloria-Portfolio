<template>
  <div id="header" class="top-0 fixed z-10 w-screen">
    <header class="bg-tranparent p-4 text-sm">
      <nav class="flex justify-between items-center tracking-widest px-40">
        <div class="logo font-extrabold text-2xl">PJ<span class="text-yellow-500">.</span></div>
        <div class="flex items-center gap-24">
          <a href="#hero">Home</a>
          <a href="#about">About</a>
          <a href="#projects">Projects</a>
          <!-- <button class="bg-yellow-500 py-2 px-4 rounded">Hire me!</button>   -->
        </div>
      </nav>
    </header>
  </div>
</template>
  
<script>
export default {
    name: 'AppHeader',
}
</script>
  
<style scoped>
</style>