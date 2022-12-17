<template>
  <div class="innerModal seondary-BG br-12">
    <span class="innerModal__button_close">&times;</span>
    <div class="innerModal__image"></div>
    <div class="innerModal__line skeleton-BG"></div>
    <div class="innerModal__stub1 skeleton-BG br-8"></div>
    <div class="innerModal__stub2 skeleton-BG br-4"></div>
    <div class="innerModal__stub2 skeleton-BG br-4"></div>
    <div class="innerModal__stub2 skeleton-BG br-4"></div>
    <div class="innerModal__stub3 skeleton-BG br-4"></div>
    <div class="innerModal__stub4 skeleton-BG br-4"></div>
    <div class="innerModal__line skeleton-BG"></div>
    <div class="delete_button">
      <div class="delete_button__text">Delete</div>
    </div>
  </div>
</template>

<style scoped>
.innerModal {
  position: absolute;
  top: 32px;
  right: -220px;

  width: 250px;
  height: 500px;

  border: 1px solid #4d4d4d;

  display: flex;
  align-items: center;
  justify-content: start;
  flex-direction: column;
}
.innerModal__button_close {
  position: absolute;
  right: 10px;
  top: -5px;
  font-size: 30px;
  font-weight: 600;
}
.innerModal__image {
  margin: 55px auto 30px auto;
  width: 130px;
  height: 130px;

  background-image: url("../assets/images/Item_Image_green.png");
}
.innerModal__line {
  margin: 0 auto 15px auto;

  width: 90%;
  height: 2px;
}
.innerModal__stub1 {
  margin: 0 auto 25px auto;
  width: 210px;
  height: 30px;
  
}
.innerModal__stub2 {
  margin: 0 auto 16px auto;
  width: 210px;
  height: 10px;
}
.innerModal__stub3 {
  margin: 0 auto 16px auto;
  width: 180px;
  height: 10px;
}
.innerModal__stub4 {
  margin: 0 auto 25px auto;
  width: 80px;
  height: 10px;
}
.delete_button {
  display: flex;
  align-items: center;
  justify-content: center;

  width: 220px;
  height: 40px;

  border-radius: 8px;

  background: #fa7272;
}
.delete_button__text {
  font-family: "SF Pro Display";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 17px;
}
</style>
