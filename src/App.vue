<template>
  <Header/>
<!--  <Header/>-->
  <div style="display: flex">
    <Aside/>
    <router-view/>
  </div>

</template>

<style>

</style>

<script>
import Header from "@/components/Header";
import Aside from "@/components/Aside";

export default {
  name: "Layout",
  components: {
    Aside,
    Header
  }
}
</script>
