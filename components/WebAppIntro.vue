<template>
  <h1>Webアプリ作成</h1>
  <div class="container">
    <div class="item">
      <img src="/building-tsubo.png" alt="" />
      <p class="app-name">落ちものゲーム</p>
    </div>
    <div class="item">
      <img src="/dounatsu-top.png" alt="" />
      <p class="app-name">日報作成アプリ</p>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  margin-top: 5em;
}
img {
  width: 300px;
}
.app-name {
  font-size: 3em;
}
.item {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
}
</style>
