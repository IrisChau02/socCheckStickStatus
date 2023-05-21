<template>
  <div>
    <div class="fullscreen-background" :style="{ 'backgroundImage': 'url(bg.png)' }">

        <div class="container-fluid h-75 d-flex align-items-center justify-content-center">
          <div class="card text-center" style="width: 30rem">
            <div class="card-header" style="font-size: 32px;">
              ☾余月宴籌號進度☾
            </div>
            <div class="card-body" style="font-size: 23px;">
              <p>現在可排隊進場籌號為：</p>
              <p>(第一輪)R1-(第二輪)A Y100</p>
              <p style="font-size: 14px;">進入順序為R, O, Y, G, B, P</p>
              <p style="font-size: 14px;">每顏色籌號為1至200號 </p>

              <p style="font-size: 20px;">注意: 現在將會發派第二輪籌號, 工作人員會在籌號手寫英文字母</p>
              <p style="font-size: 20px;">例如: R11 > A R11</p>

              <p>♡請各位耐心等候，謝謝♡ </p>
              
            </div>
          </div>
        </div>
  
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeView",
  components: {

  },
};
</script>

<style>
.card,
.card-body,
.card-title,
.card-subtitle,
hr {
  color: #191270;
  font-weight: bold;
}

.fullscreen-background {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-size: cover;
  background-position: center;
}
</style>
