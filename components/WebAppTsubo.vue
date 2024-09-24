<template>
  <div class="container">
    <div class="imgs">
      <img src="/creating-tsubo.png" alt="" />
      <img src="/building-tsubo.png" alt="" />
    </div>
    <div class="details">
      <ul>
        <li>ハッカソンで制作</li>
        <li>落とすアイテムを自分で作成→なるべく積み上げる</li>
        <li>アイテムの複雑度 * 積んだ数 でスコア算出</li>
        <li>努力賞を受賞</li>
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
