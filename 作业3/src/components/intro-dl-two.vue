<template>
  <div class="allIII">
    <div class="bigBox1">
      <div class="Bbox1-son1">
        <img
          src="../素材/home-mobile.png"
          style="width: 151px; height: 226px; margin-right: 36px"
          alt=""
        />
        <div class="box4">
          <div class="sign">现已推出</div>
          <p style="margin: 0 0 18px; color: #fff; font-size: 28px">
            {{ msg }}
          </p>
          <a href="#" style="color: white">更多移动版频道</a>
        </div>
      </div>
      <div class="Bbox1-son2">
        <div class="plate1">
          <img
            src="../素材/platform-android.03938935.png"
            style="width: 36px; height: 36px"
            alt=""
          />
          <h3 style="color: #fff;font-size: 18px">Android版Beta频道</h3>
          <img class="downlord"
            src="../素材/下载.png"
            alt=""
          />
          <img src="../素材/badge-android.0e2acc46.png"
          style="width:132px;height:39.3px" width: alt="" />
        </div>

        <div class="plate2">
          <img
            src="../素材/platform-ios.137e2f77.png"
            style="width: 36px; height: 36px"
            alt=""
          />
          <h3 style="color: #fff;font-size: 18px">iOS版 Insider Channels</h3>
          <p class="msg"><strong>当前向新用户开放</strong></p>
          <button class="btn1">
            <strong>{{ btn3 }}</strong
            ><br />
            <span style="font-size: 15px">{{ btn4 }}</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "myIDtwo",
  data() {
    return {
      msg: "加入 Microsoft Edge 移动版预览体验计划",
      btn3: "下载Beta渠道",
      btn4: "iOS版",
    };
  },
};
</script>
<style scoped>
.allIII {
  width: 99.947vw;
  height: 306.3px;
  padding: 36px 0;
  background-color: #243a5e;
  overflow: hidden;
}
.bigBox1 {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 0 75.95px;
  padding: 0 24px;
  width: 1319.282px;
  height: 306.3px;
  /* padding: 0 24px; */
  background-color: transparent;
  overflow: hidden;
}
.box4 {
  width: 424.64px;
  height: 138px;
}
.sign {
  width: 48px;
  height: 24px;
  line-height: 24px;
  background-color: #fdb814;
  color: #000;
  font-size: 12px;
  margin: 0 0 12px;
  padding: 0 12px;
}
.plate1 {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 305.81px;
  height: 282.3px;
  margin: 12px 0;
}
.downlord {
  width: 124px;
  height: 124px;
  margin: 24px 86.9px;
  border: 4px solid #fff ;
  border-radius: 3px;
}
.plate2 {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 305.81px;
  height: 282.3px;
  margin: 12px 0;
}
.msg {
  margin: 24px;
  color: #fff;
  font-size: 15px;
}
.Bbox1-son1 {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.Bbox1-son2 {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.box a:hover {
  color: #0067b8;
}
.btn1 {
    width: 190.24px;
    height: 67.2px;
    color: #fff;
    font-size: 18px;
    background-color: #0077C6;
    border: none;
    border-radius: 3px;
    padding: 12px 36px;
    /* box-shadow: 0px 2px 14px 0px gray; */

}    
.btn1:hover {
  background-color: #0267b8;
}
</style>
