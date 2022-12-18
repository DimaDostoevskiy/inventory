<template>
  <div class="frame6 primary-BORDER seondary-BG">
    <input class="frame6__input primary-BORDER skeleton-BG" type="text" />
    <span class="button-close">&times;</span>
  </div>
</template>

<style scoped>
.frame6 {
  display: flex;
  justify-content: start;
  align-items: center;

  width: 785px;
  height: 72px;

  border-radius: 12px;
}
.frame6__input {
  margin: 18px;

  width: 699px;
  height: 36px;

  border-radius: 12px;
}
.button-close {
  position: absolute;
  right: 12px;
  top: 0px;
}
</style>
