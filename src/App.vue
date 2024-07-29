<script >
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue';
import AppInnerMenu from './components/AppInnerMenu.vue';

export default {
  components: {
    AppHeader,
    AppContent,
    AppInnerMenu,
  }
}
</script>

<template>
  <div>
    <AppHeader />
    <AppContent />
    <AppInnerMenu />
  </div>
</template>

<style lang="scss">
  @use "./styles/generals.scss"
</style>
