<template>
    <div class="titlebar flex-row items-center justify-between flex w-full h-fit gap-2">
        <div class="flex flex-row">  
          <img class="size-14 rounded-full pfp-shadow" src="/pfp.jpg">
          <img class="w-48" src="/asset_logo.svg">
        </div>
        <button class="bg-[#FF93AA] p-2 rounded-lg">
          Source Code
        </button>
    </div>
</template>

<style scoped>
  .titlebar {
    border-radius: 0px 0px 30px 30px;
    background-color: rgba(255, 204, 230, 1);
    box-shadow: 2px 2px 0px 0px rgba(255, 147, 170, 1);
    padding: 5px 25px 5px 25px;
  }

  .pfp-shadow {
    box-shadow: 1px 1px 0px 0px rgba(255, 147, 170, 1);
  }
</style>
