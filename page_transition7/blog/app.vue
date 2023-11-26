<template>
  <div>


    <!-- <navbar/> -->

    <nuxt-layout>
      <NuxtPage />

    </nuxt-layout>
  </div>
</template>

<script>


</script>

<style>
.page-enter-active,
.page-leave-active{
  transition:all 0.4s;
}

.page-enter-form,
.page-leave-to{
  opacity:0;
  filter:blur(1rem);
}

</style>
