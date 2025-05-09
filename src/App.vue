<script setup lang="ts">
import Selector from './components/Selector.vue';
import { NButton , NIcon} from 'naive-ui';
import { SettingsOutline } from '@vicons/ionicons5'
</script>

<template>
  <Selector/>
  <br>
  <n-button size="large" type="primary">🥾踢踢！</n-button>
    <div class="settings-fab">
    <n-button circle type="primary" size="large">
      <n-icon>
        <SettingsOutline />
      </n-icon>
    </n-button>
  </div>
</template>

<style scoped>
.settings-fab {
  position: fixed;
  right: 24px;
  bottom: 24px;
  z-index: 1000;
}
</style>
