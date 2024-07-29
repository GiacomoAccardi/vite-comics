<script >
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue';
import AppInnerMenu from './components/AppInnerMenu.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppContent,
    AppInnerMenu,
    AppFooter
  }
}
</script>

<template>
  <div>
    <AppHeader />
    <AppContent />
    <AppInnerMenu />
    <AppFooter />
  </div>
</template>

<style lang="scss">
  @use "./styles/generals.scss"
</style>
