<template>
  <div class="container">
    <div>
      <h2>経験5年</h2>
      <div class="experience-graph">
        <div class="experience-text">
          <span>2019</span>
          <span>2020</span>
          <span>2021</span>
          <span>2022</span>
          <span>2023</span>
          <span>2024</span>
        </div>
        <div class="experience-bar"></div>
      </div>
      <div class="hobby-bar"><p>趣味2年</p></div>
      <div class="work-bar"><p>バイト3年</p></div>
    </div>
    <div class="details">
      <div>
        <img class="icon" src="/dounatsu-icon.png" alt="" />
        <p>Webアプリ作成</p>
      </div>
      <div>
        <img class="icon" src="/beenos.png" alt="" />
        <p>インターン参加</p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 95%;
}
.experience-graph {
  width: 100%;
}
.experience-bar {
  width: 100%;
  height: 30px;
  background-color: rgb(148, 173, 202);
  animation: expandWidth 2s forwards;
}
@keyframes expandWidth {
  from {
    width: 0px;
  }
  to {
    width: 100%;
  }
}
.experience-text {
  display: flex;
  justify-content: space-between;
}
.hobby-bar {
  width: calc(100% * 2 / 5);
  height: 30px;
  background-color: rgb(148, 191, 202);
  animation: hobbyWidth 2s forwards;
}
@keyframes hobbyWidth {
  from {
    opacity: 0;
    width: 5em;
  }
  to {
    opacity: 1;
    width: calc(100% * 2 / 5);
  }
}
.work-bar {
  margin-left: calc(100% * 2 / 5);
  width: calc(100% * 3 / 5);
  height: 30px;
  background-color: rgb(165, 179, 194);
  animation: workWidth 2s forwards;
}
@keyframes workWidth {
  from {
    opacity: 0;
    width: 5em;
  }
  to {
    opacity: 1;
    width: calc(100% * 3 / 5);
  }
}
.icon {
  height: 150px;
}
.details {
  display: flex;
  justify-content: space-around;
}
</style>
