<template>
  <div class="bg-white">
    <nav
      class="
        container
        px-10
        py-8
        mx-auto
        md:flex md:justify-between md:items-center
      "
    >
      <div class="flex items-center justify-between">
        <img class="h-[87px] w-[232px]" src="../assets/logo.png"/>
        <div @click="toggleNav" class="flex md:hidden">
          <button
            type="button"
          >
          <i class="material-icons">menu</i>
          </button>
        </div>
      </div>
      <ul
        :class="showMenu ? 'flex' : 'hidden'"
        class="
          flex-col
          mt-8
          space-y-4
          md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0
        "
      >
        <li class="notbold">Home</li>
        <li class="notbold">About Us</li>
        <li class="notbold flex">Products<i class="material-icons">expand_more</i></li>
        <li class="notbold">Blogs</li>
        <li class="notbold">Contact Us</li>
        <button class="h-[44px] w-[176px] bold green">BOOK A DEMO</button>
      </ul>
    </nav>
  </div>
</template>
<script>
import { ref } from 'vue';
export default {
  setup() {
    let showMenu = ref(false);
    const toggleNav = () => (showMenu.value = !showMenu.value);
    return { showMenu, toggleNav };
  },
};
</script>

<style scoped>

.bold{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 24px;
  color: #FFFFFF;
}

.notbold{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  color: #222222;
}
.material-icons.colored { color:#3966D8 }

button.green{
  background: #7BC144;
}
</style>