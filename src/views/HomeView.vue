<script setup>
</script>

<template>
  <main>
    <div class="bg-current w-full h-screen flex flex-col lg:flex-row">
      <div class="bg-slate-200 w-full h-[100px] lg:h-full lg:w-1/3 flex lg:flex-col gap-2 p-2 justify-between lg:justify-center items-center">
        <input type="checkbox" id="ham-menu-switch" hidden>
        <label for="ham-menu-switch" class="w-[60px] h-[60px] sm:hidden bg-slate-500 flex flex-col gap-2 justify-center items-center">
          <div class="w-[45px] h-[8px] bg-slate-50"></div>
          <div class="w-[45px] h-[8px] bg-slate-50"></div>
          <div class="w-[45px] h-[8px] bg-slate-50"></div>
        </label>
        <div class="w-[80px] h-[80px] bg-slate-500">logo</div>
        <div class="hidden absolute sm:static top-[98px] sm:flex lg:flex-col gap-2">
          <div class="mb-1 w-[150px] h-[40px] bg-slate-500"></div>
          <div class="mb-1 w-[150px] h-[40px] bg-slate-500"></div>
          <div class="mb-1 w-[150px] h-[40px] bg-slate-500"></div>
        </div>
        <div class="w-[60px] h-[60px] sm:hidden"></div>
      </div>
      <div class="bg-slate-400 w-full h-full flex justify-center items-center">
        <div class="box-border w-full h-full sm:w-2/3 sm:h-2/3 bg-slate-200 flex gap-2 sm:pb-4 xl:pb-2 sm:p-2 flex-wrap ">
          <div class="xl:flex-1 w-full sm:h-1/2 xl:h-full bg-stone-300"></div>
          <div class="sm:flex-1 w-full sm:w-1/2 xl:w-full sm:h-1/2 xl:h-full bg-stone-300"></div>
          <div class="sm:flex-1 w-full sm:w-1/2 xl:w-full sm:h-1/2 xl:h-full bg-stone-300"></div>
        </div>
      </div>
    </div>
  </main>
</template>
