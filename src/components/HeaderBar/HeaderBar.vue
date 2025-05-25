<script setup lang="ts">
import { NFlex } from 'naive-ui';
import MenuButton from './MenuButton.vue';
import ThemeSetButton from './ThemeSetButton.vue';
</script>
<template>
    <div class="header-bar">
        <n-flex justify="space-between">
            <div class="header-front">
                <n-flex>
                    <MenuButton />
                    <div class="title-text">Kicker</div>
                </n-flex>
            </div>
            <div class="header-bar-tail">
                <n-flex justify="end">
                </n-flex>
            </div>
        </n-flex>
    </div>
</template>
<style scoped>
.title-text {
    font-size: 20px;
    font-weight: lighter;

}

.header-bar {
    font-size: 20px;
    font-weight: lighter;
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 40px;
    background: rgba(44, 44, 44, 1);
    z-index: 1000;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1)
}
</style>
