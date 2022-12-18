<template>
  <div class="inventory seondary-BG br-12">
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
    <div class="inventory__slot br-12"></div>
  </div>
  <InventoryModalVue />
</template>

<script setup>
import InventoryModalVue from "./InventoryModal.vue";
</script>

<style scoped>
.inventory {
  display: grid;
  grid-template-columns: repeat(5, 1fr);

  width: 525px;
  height: 500px;

  border-top: 1px solid #4d4d4d;
  border-left: 1px solid #4d4d4d;
}
.inventory__slot {
  border-right: 1px solid #4d4d4d;
  border-bottom: 1px solid #4d4d4d;
}
</style>