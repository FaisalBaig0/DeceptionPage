<template>
  <header
    class="bg-white py-4 shadow-lg bg-gradient-to-r from-white to-blue-400 mb-0"
  >
    <div class="container mx-auto flex items-center justify-between">
      <div class="flex items-center space-x-2">
        <img src="../assets/background.jpg" class="w-10 h-10" />
        <p class="text-blue-900 font-bold text-2xl hover:text-green-900">
          DeceptiConf
        </p>
      </div>
      <div class="mx-auto flex items-center gap-4 px-4">
        <p class="text-blue-700 font-semibold hover:text-blue-900">
          04-06 of April,
        </p>
        <p class="text-blue-700 font-semibold hover:text-blue-900">2022</p>

        <p class="text-blue-700 font-semibold hover:text-blue-900">
          Los Angeles, CA
        </p>
      </div>
      <div>
        <a
          href="#"
          class="bg-blue-700 hover:bg-blue-400 text-white p-3 m-3 text-base focus:outline-none font-semi-bold justify-center inline-flex rounded-2xl"
          >Get Your Tickets</a
        >
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderCom",
};
</script>

<style>
header {
  margin-top: 0px;
  left: 0px;
}
</style>
