<template>
  <div
    class="delete-modal delete-modal_active seondary-BG primary-BORDER br-12"
  >
    <input
      class="delete-modal__input seondary-BG primary-BORDER br-4"
      type="text"
      placeholder=" input quantyty"
    />
    <div class="delete-modal__buttons-wraper">
      <button
        class="delete-modal__button-cancel primary-BORDER br-8"
        type="button"
      >
        cancel
      </button>
      <button
        class="delete-modal__button-confirm primary-BORDER br-8"
        type="button"
      >
        confirm
      </button>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.delete-modal {
  position: absolute;

  padding: 20px;

  display: flex;
  align-items: center;
  justify-content: start;
  flex-direction: column;

  right: 0px;
  bottom: -120px;

  width: 250px;
  height: 135px;
}
.delete-modal_active {
  right: 33px;
  bottom: 128px;
}
.delete-modal__input {
  width: 210px;
  height: 40px;
  margin: 0 auto 20px auto;
}
.delete-modal__buttons-wraper {
  display: flex;
  justify-content: space-between;
  align-items: center;

  width: 100%;
}
.delete-modal__button-cancel {
  width: 88px;
  height: 33px;
  color: #2D2D2D;
}
.delete-modal__button-confirm {
  width: 112px;
  height: 33px;
  background: #fa7272;
  color: #ffff;
}
</style>
