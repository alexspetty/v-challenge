<template>
  <div id="home">
    <SkipNavComponent />
    <AuthenticGovSiteComponent />
    <OverlayComponent />
    <MainNavigationComponent />
    <MainContentComponent />
    <FooterComponent />
  </div>
</template>

<script>
import SkipNavComponent from './SkipNavComponent.vue';
import AuthenticGovSiteComponent from './AuthenticGovSiteComponent.vue';
import OverlayComponent from './OverlayComponent.vue';
import MainNavigationComponent from './MainNavigationComponent.vue';
import MainContentComponent from './MainContentComponent.vue';
import FooterComponent from './FooterComponent.vue';

export default {
  components: {
    SkipNavComponent,
    AuthenticGovSiteComponent,
    OverlayComponent,
    MainNavigationComponent,
    MainContentComponent,
    FooterComponent
  }
};
</script>

<style scoped src="../styles.scss"></style>