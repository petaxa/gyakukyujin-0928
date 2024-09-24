<template>
  <div class="container">
    <div class="name item1">
      <img class="portrait" src="/portrait.png" alt="" />
      <h2>市村悠馬</h2>
    </div>

    <div class="overview item2">
      <div class="overview-text">
        <p>学部3年</p>
        <p>大学入学時から開発バイト</p>
        <p>Webフロントがメイン</p>
      </div>
    </div>

    <div class="myself item3">
      <ul>
        <li>所属: サイバー大学 IT総合学部 IT総合学科</li>
        <li>出身: 茨城県つくば市</li>
      </ul>
    </div>
    <div class="experiments item4">
      <ul>
        <li>
          趣味:
          <ul>
            <li>ロケット/宇宙機</li>
            <li>サッカー</li>
            <li>スキー</li>
          </ul>
        </li>
        <li>クローン病</li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
li::marker {
  content: none;
}
ul > li {
  position: relative;
  padding-left: 20px; /* マーカー分のスペースを確保 */
  display: block;
}
ul > li::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.5em;
  width: 6px; /* 縦長四角形の幅 */
  height: 20px; /* 縦長四角形の高さ */
  background-color: rgb(4, 10, 97); /* 四角形の色 */
}
ul ul li::before {
  content: none;
}
.container {
  margin-left: 15px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(2, 1fr);
  row-gap: 35px;
}
.portrait {
  width: 180px;
}
.overview {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.overview-text {
  display: flex;
  flex-direction: column;
  font-size: 30px;
}

.myself {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.myself > ul {
  height: 6em;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

.item1 {
  grid-column-start: 1;
  grid-column-end: 2;
}
.item2 {
  grid-column-start: 2;
  grid-column-end: 4;
}
.item3 {
  grid-column-start: 1;
  grid-column-end: 3;
}
.item4 {
  grid-column-start: 3;
  grid-column-end: 4;
}
</style>
