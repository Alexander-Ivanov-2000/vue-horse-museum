<template>
  <div>
    <img src="../assets/gallery_img_1.jpg">
    <img src="../assets/gallery_img_2.jpg">
    <img src="../assets/gallery_img_3.jpg">
    <img src="../assets/gallery_img_4.jpg">
  </div>
</template>

<style scoped>
div {
  /*height: 500px;
  width: 750px;
  overflow: scroll;*/

  width: 98%;
  height: 500px;
  margin: auto;
  
  display: flex;
  flex-direction: row;
  overflow: scroll;
}
img {
  height: 100%;
}
</style>