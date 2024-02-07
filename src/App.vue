<script setup>
import { useThemeConfig } from '@core/composable/useThemeConfig';
import { hexToRgb } from '@layouts/utils';
import { useTheme } from 'vuetify';
import TariffsPage from './@core/components/TariffsPage.vue';

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
      <TariffsPage/>
    </VApp>
  </VLocaleProvider>
</template>