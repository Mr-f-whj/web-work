<template>
            <div class="allV">
            <div class="box9">
                <ul>
                    <div class="list1"><strong>新增内容</strong></div>      <!--通过将父组件数组传输过来进行遍历-->
                    <li v-for="(word1,index) in list1" :key="index"><a style=" text-decoration: none;color: #616161;" href="#">{{word1}}</a></li>
                </ul>
                <ul>
                    <div class="list2">Microsoft Store</div>
                    <li v-for="(word2,index) in list2" :key="index"><a style=" text-decoration: none;color: #616161;" href="#">{{word2}}</a></li>
                </ul>
                <ul>
                    <div class="list3"><strong>教育</strong></div>
                    <li v-for="(word3,index) in list3" :key="index"><a style=" text-decoration: none;color: #616161;" href="#">{{word3}}</a></li>
                </ul>
                <ul>
                    <div class="list4"><strong>企业</strong></div>
                    <li v-for="(word4,index) in list4" :key="index"><a style=" text-decoration: none;color: #616161;" href="#">{{word4}}</a></li>
                </ul>
                <ul>
                    <div class="list5"><strong>开发人员</strong></div>
                    <li v-for="(word5,index) in list5" :key="index"><a style=" text-decoration: none;color: #616161;" href="#">{{word5}}</a></li>
                </ul>
                <ul>
                    <div class="list6"><strong>公司</strong></div>
                    <li v-for="(word6,index) in list6" :key="index"><a style=" text-decoration: none;color: #616161;" href="#">{{word6}}</a></li>
                </ul>
            </div>
            <div class="bottom">
                <div class="pic13">
                    <div><img src="../素材/地球,地理,全球.png" style="width:20px ;height:20px" alt=""></div>
                    <span style="font-size: 12px;">&nbsp;&nbsp;&nbsp;中文中国</span>
                </div>
                <ul class="list7">
                    <li v-for="(word7,index) in list7" :key="index"><a style="text-decoration: none;color: #616161;font-size: 12px;" href="#">{{word7}}</a></li>
                </ul>
            </div>

        </div>
</template>
<script>
export default {
   name: 'myFooter',
   props: ['list1','list2','list3','list4','list5','list6','list7']
}
</script>
<style scoped>
.allV {
        width: 89.954vw;
        height: 396px;
        padding: 0 4.997vw;
        margin-top: 48px;
        background-color: #f2f2f2;
    }

    .box9 {
        height: 324px;
        width: 89.954vw;
        list-style: none;
        display: flex;
        justify-content: space-between;
    }

    .box9 ul {
        margin-right: 12px;
    }

    ul .list1,
    ul .list2,
    ul .list3,
    ul .list4,
    ul .list5,
    ul .list6 {
        width: 14.203vw;
        height: 20px;
        margin: 36px 0 4px;
        color: #616161;
        background-color: transparent;
        font-size: 0.987vw;
    }

    .box9 ul li {
        width: 13.413vw;
        height: 16px;
        padding: 8px 0px;
        font-size: 0.789vw;
        text-decoration: none;
        color: #616161;
    }

    ul li:hover {
        text-decoration: underline;
        text-decoration-color: #616161;
    }

    .bottom {
        display: flex;
        justify-content: space-between;
        width: 89.954vw;
        height: 26px;
        padding: 30px 0 16px;
        background-color: transparent;
    }

    .pic13 {
        height: 24px;
        width: 85.25px;
        padding: 0 1.579vw 0 0;
        display: flex;

    }

    /* .pic12 ul {
        display: inline-block;
    } */
    .list7 {
        width: 55.032vw;
        height: 20px;
        margin: 3px 0;
        list-style: none;
    }

    .list7 li {
        display: inline-block;
        color: #616161;
        margin: 0 1.25vw 4px 0;
        font-size: 0.789vw;
    }

    .list7 a:hover {
        text-decoration: underline;
        text-decoration-color: #616161;
    }

    .pic13 span:hover {
        text-decoration: underline;
        text-decoration-color: #616161;
    }
</style>