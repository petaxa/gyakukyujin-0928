<template>
  <h1>Webアプリ作成 -日報作成アプリ</h1>
  <div class="container">
    <div class="imgs">
      <img src="/dounatsu-top.png" alt="" />
      <img src="/dounatsu-nippo.png" alt="" />
    </div>
    <div class="details">
      <ul>
        <li>アルバイトの日報作成を楽にするために開発</li>
        <li>フォームに入力→クリップボードにコピー→ペーストして送信</li>
        <li>3年前に作成→リファクタ中</li>
      </ul>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  height: 80%;
}
img {
  width: 300px;
}
.imgs {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}
.details {
  margin-left: 3em;
  margin-top: 5em;
}
.details li::marker {
  color: rgb(111, 132, 247);
}
.details li {
  font-size: 1.2em;
}
</style>
