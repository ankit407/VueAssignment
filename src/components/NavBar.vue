<template>
  <nav class="bg-black p-4">
    <div class="flex">
      <div class="text-4xl text-semibold ml-28">
        <img src="../assets/logo1.png" />
      </div>
      <div
        class="float-right text-xl font-semibold mx-3 mt-4 text-white hover:bg-gray-700 ml-auto cursor-pointer"
      >
        Home
      </div>
      <div
        class="float-right text-xl font-semibold mx-3 mt-4 text-white hover:ring-gray-700 cursor-pointer"
      >
        About us
      </div>
      <div
        class="float-right text-xl font-semibold mx-3 mt-4 text-white hover:bg-gray-700 cursor-pointer"
      >
        Services
      </div>
      <div
        class="float-right text-xl font-semibold mx-3 mt-4 text-white hover:bg-gray-700 cursor-pointer"
      >
        Blog
      </div>
      <div
        class="float-right text-xl font-semibold mt-4 text-white hover:bg-gray-700 cursor-pointer"
      >
        Contact us
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  name: "NavBarView",
};
</script>
