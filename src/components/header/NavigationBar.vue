src > components > header > NavigationBar.vue
<template>
  <div
    class="header__navbar row justify-content-between align-items-center"
    style="width: 450px"
  >
    <search-menu></search-menu>
    <signup-menu></signup-menu>
  </div>
</template>

<script setup>
import SearchMenu from "../header/SearchMenu.vue";
import SignupMenu from "../header/SignupMenu.vue";

// export default {
//   components: {
//     SearchMenu,
//     SignupMenu,
//   },
// };
</script>
