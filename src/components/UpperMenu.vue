<template>
  <div>
    <img src="../assets/vdnh_side_logo.png" class="logo">
    <span class="menuItem">События</span>
    <span class="menuItem">Посетителям</span>
    <span class="menuItem">Билеты</span>
    <span class="menuItem">Скидки</span>
    <span class="menuItem">Новости</span>
    <span class="menuItem">Контакты</span>
    <span class="menuItem">Ещё...</span>
  </div>
</template>

<style scoped>
div {
  border: 1px solid black;
  border-radius: 5px;
  height: 75px;
  width: 98%;
  margin: auto;

  display: flex;
  align-items: center;
}
.logo {
  height: 60px;
}
.menuItem {
  padding-left: 30px;
}
</style>