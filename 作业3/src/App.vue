<template>
<div id="app">
  <div class="all">
    <myNav/>
    <myIDone/> 
    <myIDtwo/>
    <myPara1-1 :Title="info.title1_1" :Para="info.para1_1" :imgSrc="info.src1_1"/>
    <myPara2-1 :Title="info.title1_2" :Para="info.para2_1" :imgSrc="info.src2_1"/>
    <myPara1-2 :Title="info.title2_1" :Para="info.para1_2" :imgSrc="info.src1_2"/>
    <myPara2-2 :Title="info.title2_2" :Para="info.para2_2" :imgSrc="info.src2_2"/>
    <myFooter :list1="word1" :list2="word2" :list3="word3" :list4="word4" :list5="word5" :list6="word6" :list7="word7" />
  </div>
  
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import MyNav from "./components/myNav.vue";
import myIDone from "./components/intro-dl-one.vue";
import myIDtwo from "./components/intro-dl-two.vue";
import myPara1 from "./components/para1.vue";
import myPara2 from "./components/para2.vue";
import myFooter from "./components/footer.vue"
// import demo from "./components/demo.vue"

export default {
  name: "App",
  components: {  
    'myNav': MyNav,
    'myIDone': myIDone,
    'myIDtwo': myIDtwo,
    'myPara1-1': myPara1,
    'myPara2-1': myPara2,
    'myPara1-2': myPara1,
    'myPara2-2': myPara2,
    'myFooter': myFooter,
  },
  data () {
    return {
        info: {
          title1_1: '成为 Microsoft Edge 预览体验成员',
          para1_1: '我们的预览体验成员社区在帮助构建 Microsoft Edge 方面发挥了重大作用，而且我们的创新从未停止。 如果你想要了解我们的后续工作，我们诚邀你下载我们的预览渠道并加入预览体验成员社区。 届时你将可以抢先预览新功能，并且有机会在开发过程中与 Microsoft Edge 团队合作。 你的反馈和想法可以帮助我们改进，因此我们希望你能加入我们。 单击下载以开始使用!',
          src1_1: require('../src/素材/home-panel-01.524516ff.png'),//动态传输图片路径
          //
          title2_1: '为大众打造更好的互联网空间',
          para2_1: '我们在 Microsoft Edge 的开发过程中采用了 Chromium 开源项目，以此来为我们的客户提供更好的网站兼容性，并为所有的网站开发人员降低网站的碎片化程度。 我们将继续为 Chromium 项目做出积极贡献。 到目前为止，我们已经兑现了 1,700 多项承诺，并期待继续积极参与社区互动，为大众打造更好的互联网空间。 如需详细了解我们的贡献，请参阅 GitHub 上的 Microsoft Edge “Explainers”，并查看我们的源代码发布。',
          src2_1: require('../src/素材/home-panel-02.0b0c5f77.png'),
          //
          title1_2: '查看 Microsoft Edge Insider Channels',
          para1_2: '我们提供三个预览渠道：Beta、Dev 和 Canary。 这些频道适用于所有受支持版本的 Windows、Windows Server 以及 macOS。 Beta 版频道可以提供最稳定的预览版体验，每 4 周更新一次。 开发频道每周更新一次，稳定性略逊于 Beta 版，但优于 Canary。 对于想要在相对稳定的版本内获取最新更新的人员，Dev 是一个不错的选择。 如果你想要查看我们昨天的工作并获取每日更新，那么 Canary 可能是你的理想预览渠道。 安装预览渠道不需要卸载 Microsoft Edge 的已发布版本，你可以同时安装多个版本。 若要详细了解不同的渠道并开始使用，请转到 下载页。',
          src1_2: require('../src/素材/home-panel-03.a937cdae.png'),
          //
          title2_2: '我们乐于倾听!',
          para2_2: 'Microsoft Edge 团队希望倾听你的声音。 在使用预览渠道时，请务必通过工具栏上的“发送反馈”按钮来分享你的反馈。 你还可以访问我们的 Microsoft Edge 预览体验成员论坛或在 Twitter 上关注 @MSEdgeDev。 我们会定期分享来自预览体验成员社区的热门反馈总结，以便你可以了解最受期待的功能、最新出现的问题以及你的反馈对产品产生的影响。 衷心希望你加入社区。如果尚未加入，我们期待倾听你的想法！',
          src2_2: require('../src/素材/home-panel-04.7ea71f0e.png'),
        },

        word1:['Microsoft 365','Surface Laptop 2','Surface Go','Windows 11 应用程序'],
        word2:['帐户个人资料','下载中心','订单跟踪'],
        word3:['Microsoft','教育领域适合学生的 Office','适用于学校的 Office365','Microsoft Azure 教育领域'],
        word4:['Azure','AppSource','汽车','政府机构','医疗保健','制造业','金融服务','零售业'],
        word5:['Microsoft Visual Studio','Windows 开发人员中心','开发人员中心','Microsoft 开发人员计划','第9频道','Microsoft 365 开发人员中心','Microsoft 365 开发人员计划'],
        word6:['招贤纳士','关于 Microsoft','公司新闻','Microsoft 隐私','投资人','安全性'],
        word7:['与 Microsoft 联系','隐私','使用条款','商标','关于我们的广告','京ICP备09042378号-6','京公网安备','11010802023178','© Microsoft 2021'],
    }
  }
};
</script>
<style lang="css">
body,ul,p,h1,h3,h2 {
  padding: 0;
  margin: 0;
}
.all {
  width: 99.947vw;
}
</style>
