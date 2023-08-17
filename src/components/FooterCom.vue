<template>
  <footer class="footer">
    <div
      class="relative mx-auto my-20 p-3 grid max-w-2xl gap-x-32 gap-y-12 xl:max-w-none bg-gradient-to-r from-white to-blue-400 mb-0"
    >
      <div>
        <p class="font-display font-medium text-4xl text-blue-900">
          Stay up to date
        </p>
        <p class="mt-4 text-blue-900 text-lg tracking-tight">
          Get updates on all of our events and be the first to get notified when
          tickets go on sale.
        </p>
      </div>
      <form>
        <h3 class="text-lg text-blue-900 font-semibold tracking-tight">
          Sign up to our newsletter
          <span aria-hidden="true">↓</span>
        </h3>
        <input
          type="text"
          v-model="footer"
          required
          placeholder="Enter Address"
          aria-label="Enter Address "
          class="bg-transparent pl-6 text-base text-slate-900 placeholder:text-slate-400 focus:outline-none flex-auto mt-5 rounded-2xl bg-white shadow-xl focus-within:ring-2 focus-within:ring-blue-900 py-2.5 pr-2.5 w-80 shadow-blue-100"
        />
        <button
          type="submit"
          class="bg-blue-600 rounded-2xl inline-flex justify-center font-semibold text-white hover:bg-blue-400 focus:outline-none m-3 p-3"
        >
          SignUp today
        </button>
      </form>
      <div class="flex items-center justify-between my-3">
        <div class="flex items-center space-x-2 my-3 ml-10">
          <img src="../assets/background.jpg" class="w-10 h-10" />
          <p class="text-blue-900 font-bold text-2xl hover:text-green-900">
            DeceptiConf
          </p>
        </div>
        <p class="text-base text-slate-900 p-2 -tracking-tighter font-bold">
          Copyright © 2023 DeceptiConf, LLC. All rights reserved.
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterCom",
  data() {
    return {
      footer: "",
    };
  },
};
</script>

<!-- <style>
.footer{
    position: fixed;
    bottom: 0px;
    left: 0px;
    width: 100%;

}
</style> -->
