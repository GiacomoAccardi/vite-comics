<script >
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue';
import AppSections from './components/AppSections.vue';

export default {
  components: {
    AppHeader,
    AppContent,
    AppSections,
  }
}
</script>

<template>
  <div>
    <AppHeader />
    <AppContent />
    <AppSections />
  </div>
</template>

<style lang="scss">
  @use "./styles/generals.scss"
</style>
