<script setup>
import { useThemeConfig } from '@core/composable/useThemeConfig';
import { hexToRgb } from '@layouts/utils';
import { useTheme } from 'vuetify';
import ManagerPage from './@core/components/ManagerPage.vue';
// import MainPage from './@core/components/MainPage.vue';
// import NewsPage from './@core/components/NewsPage.vue';
// import RefferalsPage from './@core/components/RefferalsPage.vue';



const {
  syncInitialLoaderTheme,
  syncVuetifyThemeWithTheme: syncConfigThemeWithVuetifyTheme,
  isAppRtl,
  handleSkinChanges,
} = useThemeConfig()

const { global } = useTheme()

// ℹ️ Sync current theme with initial loader theme
syncInitialLoaderTheme()
syncConfigThemeWithVuetifyTheme()
handleSkinChanges()
</script>

<template>
  <VLocaleProvider :rtl="isAppRtl">
    <!-- ℹ️ This is required to set the background color of active nav link based on currently active global theme's primary -->
    <VApp :style="`--v-global-theme-primary: ${hexToRgb(global.current.value.colors.primary)}`">
      <!-- <RouterView />
      <ScrollToTop /> -->
      <ManagerPage/>
    </VApp>
  </VLocaleProvider>
</template>