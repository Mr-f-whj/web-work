<template>
  <div class="allIV">
    <div class="IV-son">
      <div class="Pic">
        <img :src="imgSrc" style="width: 479.96px; height: 275.01px" alt="" />
      </div>
      <div>
        <h2 class="Title">{{ Title }}</h2>
        <p class="Para">{{ Para }}</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "myPara2",
  props: ["Title", "Para", "imgSrc"],
};
</script>
<style scoped>
.allIV {
  width: 89.953vw;
  height: 327.01px;
  margin: 0 75.95px;
  color: #262626;
}
.IV-son {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 89.953vw;
  height: 279.01px;
  margin: 24px 0;
}
.Title {
  font-size: 34px;
  color: #262626;
  margin: 0 0 12px;
}
.Para {
  font-size: 18px;
  color: #262626;
  margin: 0 12px;
}
.Pic {
  margin: 0 24px;
  padding: 0 41.725px 0 0;
}
</style>