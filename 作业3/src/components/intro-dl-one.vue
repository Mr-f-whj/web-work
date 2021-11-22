<template>
  <div class="allII">
    <div class="bigBox">
      <div class="box1">
        <h1 class="title">{{title}}</h1>
        <p class="content">{{contents}}</p>
        <button class="btn" >
            <strong>{{btn1}}</strong><br>
            <span style="font-size: 15px">{{btn2}}</span>
        </button>
        <p class="more" style="margin: 7px;"><a href="#" style="color: #0067B8">更多平台和渠道</a></p>   <!--值得学习-->
      </div>
      <img src="../素材/home-hero.b831069c.png" style="width: 626.4px;height: 310.56px" alt="">
      
    </div>
  </div>
</template>
<script>
export default {
  name: "myIDone",

  data() {
    return {
        title: '查看即将推出的内容!',
        contents: 'Microsoft Edge 预览频道现已推出移动版！请访问下载页面，根据你的移动设备选择要安装的版本。想成为第一批预览新增功能的人吗？我们将持续更新包含最新功能的 Insider Channels，请立即下载并加入 Microsoft Edge 预览体验成员社区。',
        btn1: '下载 beta 渠道',
        btn2: 'Windows 10 / 11版',
    };
  },
};
</script>
<style scoped>
a {
    text-decoration: none;
}
.allII {
    width: 89.967vw;
    height: 314.58px;
    margin: 18px 75.95px 0 75.95px;
    padding: 36px 0;
}
.bigBox {
    display: flex;
    width: 1400.15px;
    height: 314.58px;
}
.box1 {  
  width: 773.59px;
  height: 314.58px;
  padding: 0 0 0 24px;
  text-align: center;
}
.title {
  text-align: center;
  font-size: 52px;
  margin: 8px 0;
}
.content {
    text-align: center;
    font-size: 20px;
    margin: 0 0 36px;
}
.btn {
    width: 312px;
    height: 67.2px;
    color: #fff;
    font-size: 18px;
    background-color: #0077C6;
    border: none;
    border-radius: 3px;
    padding: 12px 24px;
    box-shadow: 0px 2px 14px 0px gray;

} 
.more:hover a {
  border-bottom: 1px solid #0067B8;
}
.btn:hover {
  background-color: #0267b8;
}   
</style>
