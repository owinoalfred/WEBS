<template>

    <div class="menu  flex "><router-link to="/">
      <button
        type="button"
        class="bg-indigo-700 px-4 py-2 rounded hover:bg-pink-500"
      >
        Home
      </button>
      </router-link>
      <router-link to="/Services">
      <button
        type="button"
        class=" bg-indigo-700 px-4 py-2 rounded hover:bg-pink-300"
      >
        Services
      </button>
      </router-link>
      <router-link to="/Pricing">
      <button
        type="button"
        class=" bg-indigo-700 px-4 py-2  rounded hover:bg-pink-200"
      >
        Pricing
      </button>
      </router-link>
      <router-link to="/About">
      <button
        type="button"
        class=" bg-indigo-700 px-4 py-2 rounded hover:bg-pink-200"
      >
        About
      </button>
      </router-link>
      <router-link to="/Tools">
      <button
        type="button"
        class="rounded  bg-indigo-700 px-4 py-2 hover:bg-pink-200 border-pink-600"
      >
        Tools
      </button>
      </router-link>
    </div>
    <div class="name "></div>
    <div class="photo"></div>

</template>
<script>
export default {

};
</script>
