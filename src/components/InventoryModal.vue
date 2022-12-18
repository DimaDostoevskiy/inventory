<template>
  <div class="inventory-modal seondary-BG br-12">
    <span class="button-close">&times;</span>
    <div class="inventory-modal__image"></div>
    <div class="inventory-modal__line skeleton-BG"></div>
    <div class="inventory-modal__stub1 skeleton-BG br-8"></div>
    <div class="inventory-modal__stub2 skeleton-BG br-4"></div>
    <div class="inventory-modal__stub2 skeleton-BG br-4"></div>
    <div class="inventory-modal__stub2 skeleton-BG br-4"></div>
    <div class="inventory-modal__stub3 skeleton-BG br-4"></div>
    <div class="inventory-modal__stub4 skeleton-BG br-4"></div>
    <div class="inventory-modal__line skeleton-BG"></div>
    <div class="delete-button">
      <div class="delete-button__text">Delete</div>
    </div>
  </div>
  <DeleteItemModalVue />
</template>

<script setup>
import DeleteItemModalVue from "./DeleteItemModal.vue";
</script>

<style scoped>
.inventory-modal {
  position: absolute;

  display: flex;
  align-items: center;
  justify-content: start;
  flex-direction: column;

  top: 32px;
  right: -220px;

  width: 250px;
  height: 500px;

  border: 1px solid #4d4d4d;
}
.inventory-modal_active {
  right: 33px;
}
.button-close {
  position: absolute;
  right: 10px;
  top: -5px;

}
.inventory-modal__image {
  margin: 55px auto 30px auto;
  width: 130px;
  height: 130px;

  background-image: url("../assets/images/Item_Image_green.png");
}
.inventory-modal__line {
  margin: 0 auto 15px auto;

  width: 90%;
  height: 2px;
}
.inventory-modal__stub1 {
  margin: 0 auto 25px auto;
  width: 210px;
  height: 30px;
}
.inventory-modal__stub2 {
  margin: 0 auto 16px auto;
  width: 210px;
  height: 10px;
}
.inventory-modal__stub3 {
  margin: 0 auto 16px auto;
  width: 180px;
  height: 10px;
}
.inventory-modal__stub4 {
  margin: 0 auto 25px auto;
  width: 80px;
  height: 10px;
}
.delete-button {
  display: flex;
  align-items: center;
  justify-content: center;

  width: 220px;
  height: 40px;

  border-radius: 8px;

  background: #fa7272;
}
.delete-button:hover {
  background: #ff8888;
}
.delete-button__text {
  font-family: "SF Pro Display";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 17px;
}
</style>
