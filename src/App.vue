<script setup lang="ts">
import { useSettingsStore } from '@/stores/settings'
import ContainerBox from '@/components/ContainerBox.vue';

const settingsStore = useSettingsStore()

</script>

<template>
  <div class="crt"></div>
  <div class="root-container">
    <ContainerBox>
      <h1>Hello World!</h1>
    </ContainerBox>
    <br>
    <ContainerBox>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </ContainerBox>
    <br>
    <ContainerBox>
      <img src="@/assets/images/marty.jpg" alt="Marty" height="500">
    </ContainerBox>
  </div>
</template>

<style scoped lang="scss">
</style>
