<template>
  <h1>インターン</h1>
  <h2>2つの就業型インターンに参加</h2>
  <div class="container">
    <div>
      <h3>手ごたえあり</h3>
      <ul>
        <li>コミュニケーション</li>
        <li>Vueの実力</li>
        <li>コードリーディング</li>
      </ul>
    </div>
    <div>
      <h3>働く環境へのイメージがついた</h3>
      <ul>
        <li>つくばから東京へ通うのは週2が限度</li>
        <li>非同期コミュニケーションの重要性と限界</li>
        <li>「制限」の便利さ</li>
      </ul>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  margin-top: 3em;
}
.container h3 {
  margin-bottom: 0.5em;
}
li {
  font-size: 1.2em;
}
li::marker {
  color: rgb(111, 132, 247);
}
</style>
