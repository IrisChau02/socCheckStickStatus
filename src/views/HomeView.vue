<template>
  <div>
    <div class="fullscreen-background" :style="{ 'backgroundImage': 'url(bg.png)' }">

        <div class="container-fluid h-75 d-flex align-items-center justify-content-center">
          <div class="card text-center" style="width: 30rem">
            <div class="card-header" style="font-size: 32px;">
              ☾余月宴籌號進度☾
            </div>
            <div class="card-body" style="font-size: 24px;">
              <p>現在可排隊進場籌號為：xxxxxx</p>
            <br>
              <p>進入順序為紅橙黃綠藍紫</p>
              <p>進入順序為紅, 橙, 黃, 綠, 藍, 紫</p>
              <p>現階段每個籌號顏色為1至100號 </p>
              <br>
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
