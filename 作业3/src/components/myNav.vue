<template>
    <div class="allI">
            <div class="listI">                     <!--设置动态行内样式  :style='{width:"108px" ,height:"23px"}'-->
              <a href="#" class="pic1" ><img src="../素材/RE1Mu3b.png" style="width: 108px;height: 23px" alt=""></a>
              <div class="line" ></div>
              <a href="#" class="word1">Microsoft Edge Insider</a>
            </div>
            <div class="listII_dad">
            <ul class="listII">
                <li class="one"><a href="">下载</a></li>
                <li class="two"><a href="">最新动态</a></li>
                <li><a href="">下一步</a></li>
                <li><a href="">大型企业</a></li>
                <li><a href="">社区</a></li>
                <li><a href="">支持</a></li>
            </ul>
            </div>
            <div class="listIII">
                <div class="listIII-1">
                    <span>所有Microsoft</span>
                    <img src="../素材/向下箭头.png" class="pic2" style="width: 14px;height: 16px" alt="">
                </div>
                <div class="listIII-2" title="在所有Microsoft中搜索">
                    <a href="#">搜索</a>
                    <img src="../素材/搜索.png" class="pic3" style="width: 18px;height: 18px" alt="">
                </div>
            </div>
        </div>
</template>
<script>
export default {
    name: 'myNav',
    
}
</script>
<style scoped>
a {
    text-decoration: none;
    color: #262626;
}
.allI {
    display: flex;
    justify-content: space-between;
    width: 89.953vw;
    padding: 0 4.997vw 2px 4.997vw;
    
}
.listI {
    display: flex;
    width: 362px;
    height: 54px;
}
.pic1 {
    width: 120px;
    height: 23px;
    margin: 16px 6px 16px 10px;
}
.line {
    border-left: 2px solid #000;
    height: 24px;
    margin: 16px 7px;
}
.word1 {
    width: 198px;
    margin: 16px 8px 16px 10px;
    color: #262626;
    font-size: 17px;
    font-weight: 600;

}
.listII_dad {
    width: 67.5vw;
    height: 54px;
}
.listII {
    list-style: none;
    display: flex;
    
}
.listII li {
    /* width: 28px; */
    height: 21px;
    margin: 20px 10px 10px;
    font-size: 13px;
    color: #262626;
    /* margin: 10px; */
}
.listIII {
    display: flex;
    width: 300px;
    height: 54px;
}
.listIII-1 {
    height: 21px;
    padding: 17px 2px 16px 15px;
    color: #262626;
    font-size: 13px;  
}
.pic2 {
    margin: 2px 0 0 4px; 

}
.pic3 {
    margin: 2px 0 0 4px;
}
.listIII-2 {
    height: 19px;
    padding: 15px 2px 20px 9px;
    color: #262626;
    font-size: 13px;  
}
.listIII-1 span {
    font-size: 13px;
    margin-bottom: 4px; 
}
.listIII-2 a {
    font-size: 13px;
}
.word1:hover {
    border-bottom: 2px solid #000;
}
.listII li a:hover ,
.listIII-1:hover span,
.listIII-2:hover a {
    border-bottom: 3px solid #000;
} 
</style>