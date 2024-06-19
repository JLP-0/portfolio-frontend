<script setup>
import FooterVue from "./components/Footer.vue";
import NavbarVue from "./components/Navbar.vue";
import Personal_InformationVue from "./components/Personal_Information.vue";


</script>

<template>
  <header>
    <NavbarVue/>    
  </header>

  <main class="bg-slate-900">
   <Personal_InformationVue/>
  </main>

    <FooterVue/>

</template>

<style scoped>

</style>


