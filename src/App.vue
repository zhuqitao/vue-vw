<template>
  <div class="wrapper">
    <div class="box1"></div>
    <div class="box2">
      asd
    </div>
    <div class="box3">asd</div>
    <div class="box4"></div>
    <div class="box5"></div>
    <div class="border">border</div>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
}
</style>

<style scoped>
.wrapper div {
  height: 1rem;
}
.box1 {
  /* 750 * 20% */
  width: 150px;
  background-color: coral;
}
.box2 {
  /* 750 * 40% */
  width: 300px;
  font-size: 20px;/*px*/
  background-color: skyblue;
}
.box3 {
  /* 750 * 60% */
  width: 450px;/*no*/
  font-size: 30px;/*px*/
  background-color: palegreen;
}
.box4 {
  /* 750 * 80% */
  width: 600px;
  background-color: wheat;
}
.box5 {
  /* 750 * 100% */
  width: 750px;
  background-color: darkred;
}
.border{
  height: 10px;
  width: 10rem;
  border-bottom: solid 1px #000;
}
</style>
