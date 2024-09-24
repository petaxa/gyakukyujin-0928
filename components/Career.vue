<template>
  <div class="container">
    <h2 class="triangle-item">チームビルディング</h2>
    <h2 class="triangle-item">技術力</h2>
    <h2 class="triangle-item">当事者意識</h2>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  margin-left: 6em;
  margin-top: 4em;
  width: 65%;
  height: 250px;
  position: relative;
}

.triangle-item {
  position: absolute;
}

.triangle-item:nth-child(1) {
  top: 0;
  left: calc(50% - 3.5em);
}

.triangle-item:nth-child(2) {
  bottom: 0;
  left: 1.5em;
  transform: translateX(0);
}

.triangle-item:nth-child(3) {
  bottom: 0;
  right: -2.5em;
  transform: translateX(0);
}
</style>
