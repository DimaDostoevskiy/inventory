<template>
    <div class="frame2">
        <div class="frame2__image"></div>
        <div class="frame2__skeleton1 skeletons-bg"></div>
        <div class="frame2__skeleton2 skeletons-bg"></div>
        <div class="frame2__skeleton3 skeletons-bg"></div>
        <div class="frame2__skeleton4 skeletons-bg"></div>
        <div class="frame2__skeleton5 skeletons-bg"></div>
        <div class="frame2__skeleton6 skeletons-bg"></div>
        <div class="frame2__skeleton7 skeletons-bg"></div>
    </div>
</template>

<style scoped>
.frame2 {
    box-sizing: border-box;
    position: absolute;
    width: 236px;
    height: 500px;
    left: 32px;
    top: 32px;

    /* Seondary BG */

    background: #262626;
    border: 1px solid #4D4D4D;
    border-radius: 12px;

    display: flex;
    align-items: center;
    justify-content: start;
    flex-direction: column;
}

.frame2__image {
    margin: 14px 0 20px 0;
    background-image: url('../assets/images/frame2_image.png');
    width: 208px;
    height: 240px;
}

.frame2__skeleton1 {
    width: 190px;
    height: 26px;
    border-radius: 8px;
    margin-bottom: 24px;
}

.frame2__skeleton2 {
    width: 155px;
    height: 10px;
    border-radius: 4px;
    margin-bottom: 16px;
}

.frame2__skeleton3 {
    width: 190px;
    height: 10px;
    border-radius: 4px;
    margin-bottom: 16px;
}

.frame2__skeleton4 {
    width: 170px;
    height: 10px;
    border-radius: 4px;
    margin-bottom: 16px;
}

.frame2__skeleton5 {
    width: 160px;
    height: 10px;
    border-radius: 4px;
    margin-bottom: 16px;
}

.frame2__skeleton6 {
    width: 140px;
    height: 10px;
    border-radius: 4px;
    margin-bottom: 24px;
}

.frame2__skeleton7 {
    width: 80px;
    height: 10px;
    border-radius: 4px;
}

.skeletons-bg {
    background: linear-gradient(90deg, #3C3C3C 0%, #444444 51.04%, #333333 100%);
}
</style>