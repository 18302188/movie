<template>

    <div id="a" >
        <h1>豆瓣电影排行榜</h1>
        <h3 style="color: #30ac4f">· · · · · ·豆瓣新片榜 · · · · · ·</h3>
        <!--<el-divider  content-position></el-divider>-->
        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
        <el-row >
            <el-col span="4">
                <img src='../assets/6.jpg' width="140" height="200">
            </el-col>
            <div class="b">
                <a href="#" style="text-decoration:none">
                    <p style="color: #3377aa">
                        爱尔兰人 / 爱尔兰杀手(港) / 听说你刷房子了
                    </p>
                </a>
            </div>
            <div class="b">
              {{title1}}
            </div>
            <span class="c">
<div style="float:left;">
        <el-rate
                v-model="value6"
                disabled
                show-score
                text-color="#ff9900"
                score-template="{value}">
        </el-rate>
</div>
    <div style="float:left;margin-left:10px;font-size: 13px">(145820评价)</div>
                </span>
        </el-row>
        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
        <el-row >
            <el-col span="4">
                <a href="http://localhost:8080/movie">
                    <img src='../assets/1.jpg' width="140" height="200">
                </a>
            </el-col>
            <div class="b" >
                <a href="http://localhost:8080/movie" style="text-decoration:none">
                    <p style="color: #3377aa">
                        小丑 / 小丑起源电影：罗密欧 / Romeo
                    </p>
                </a>
            </div>
            <div class="b" >
              {{title1}}
            </div>

            <span class="c">
<div style="float:left;">
     <el-rate
             v-model="value1"
             disabled
             show-score
             text-color="#ff9900"
             score-template="{value}">
        </el-rate>
</div>
    <div style="float:left;margin-left:10px;font-size: 13px">(379190评价)</div>
                </span>


        </el-row>
        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
        <el-row>
            <el-col span="4">
                <a href="http://localhost:8080/movie2">
                    <img src='../assets/3.jpg' width="140" height="200">
                </a>
            </el-col>
            <div class="b">
                <a href="http://localhost:8080/movie2" style="text-decoration:none">
                    <p style="color: #3377aa">
                        婚姻故事
                    </p>
                </a>
            </div>
            <div class="b">
                {{title3}}
            </div>
            <span class="c">
<div style="float:left;">
        <el-rate
                v-model="value3"
                disabled
                show-score
                text-color="#ff9900"
                score-template="{value}">
        </el-rate>
</div>

    <div style="float:left;margin-left:10px;font-size: 13px">(100233评价)</div>
                </span>
        </el-row>
        <el-row>
            <el-col span="4">
                <a href="http://localhost:8080/movie1">
                    <img src='../assets/2.jpg' width="140" height="200">
                </a>
            </el-col>
            <div class="b">
                <a href="http://localhost:8080/movie1"style="text-decoration:none">
                    <p style="color: #3377aa">
                        好莱坞往事 / 从前，有个荷里活(港) / 从前，有个好莱坞...(台)
                    </p>
                </a>
            </div>
            <div class="b">
               {{title2}}
            </div>
            <span class="c">
<div style="float:left;">
        <el-rate
                v-model="value2"
                disabled
                show-score
                text-color="#ff9900"
                score-template="{value}">
        </el-rate>
</div>
    <div style="float:left;margin-left:10px;font-size: 13px">(549210评价)</div>
                </span>
        </el-row>

        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
        <el-row>
            <el-col span="4">
                <img src='../assets/5.jpg' width="140" height="200">
            </el-col>
            <div class="b">
                <a href="#" style="text-decoration:none">
                    <p style="color: #3377aa">
                        克劳斯：圣诞节的秘密 / 圣诞老人
                    </p>
                </a>
            </div>
            <div class="b">
               {{title5}}
            </div>
            <span class="c">
<div style="float:left;">
        <el-rate
                v-model="value5"
                disabled
                show-score
                text-color="#ff9900"
                score-template="{value}">
        </el-rate>
</div>
    <div style="float:left;margin-left:10px;font-size: 13px">(215000评价)</div>
                </span>
        </el-row>

        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
        <el-row>
            <el-col span="4">
                <img src='../assets/7.jpg' width="140" height="200">
            </el-col>
            <div class="b">
                <a href="#" style="text-decoration:none">
                    <p style="color: #3377aa">
                        攀登者
                    </p>
                </a>
            </div>
            <div class="b">
                {{title7}}

            </div>
            <span class="c">
<div style="float:left;">
        <el-rate
                v-model="value7"
                disabled
                show-score
                text-color="#ff9900"
                score-template="{value}">
        </el-rate>
</div>
    <div style="float:left;margin-left:10px;font-size: 13px">(254823评价)</div>
                </span>
        </el-row>
        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
        <el-row>
            <el-col span="4">
                <img src='../assets/8.jpg'width="140" height="200">
            </el-col>
            <div class="b">
                <a href="#" style="text-decoration:none">
                    <p style="color: #3377aa">
                        准备好了没 / 弑婚游戏(台) / 爆血新婚夜(港)
                    </p>
                </a>
            </div>
            <div class="b">
               {{title8}}
            </div>
            <span class="c">
<div style="float:left;">
        <el-rate
                v-model="value8"
                disabled
                show-score
                text-color="#ff9900"
                score-template="{value}">
        </el-rate>
</div>
    <div style="float:left;margin-left:10px;font-size: 13px">(562482评价)</div>
                </span>
        </el-row>
        <hr STYLE="BORDER:0.5px dashed; color:rgba(203,203,203,0.75)"></hr>
    </div>

    <!--<div class="e">-->

    <!--</div>-->


</template>

<script>
    //    import ElRate  from "../../node_modules/element-ui/packages/rate/src/main.vue";

    export default {
//        components: {ElRate},
        data:function() {
            return {


                title1:"2019-09-27(纽约电影节) / 2019-11-01(美国点映) / 2019-11-27(美国网络) / 罗伯特·德尼罗 / 阿尔·帕西诺 / 乔·佩西 / 安娜·帕奎因 / 杰西·普莱蒙 / 哈威·凯特尔 / 斯蒂芬·格拉汉姆 / 鲍比·坎纳瓦尔 / 杰克·休斯顿 / 阿莱卡萨·帕拉迪诺 / 凯瑟琳·纳杜奇...",
                title2:"2019-05-21(戛纳电影节) / 2019-07-26(美国) / 2019(中国大陆) / 莱昂纳多·迪卡普里奥 /布拉德·皮特 / 玛格特·罗比 / 埃米尔·赫斯基 / 玛格丽特·库里 / 蒂莫西·奥利芬特 /茱莉亚·巴特斯 / 奥斯汀·巴特勒 / 达科塔·范宁 / 布鲁斯·邓恩",
                title3:" 2019-08-29(威尼斯电影节) / 2019-12-06(美国) / 斯嘉丽·约翰逊 / 亚当·德赖弗 / 梅里特·韦弗 / 劳拉·邓恩 / 雷·利奥塔 / 朱丽·哈基提 / 马克·奥布莱恩 / 华莱士·肖恩 / 阿伦·阿尔达 /凯尔·柏海莫 / 米奇·萨姆纳 / 艾奇·罗伯逊 / 马修·马希尔",
                title4:"2019-10-23(韩国) / 2019-11-07(中国香港) / 郑有美 / 孔侑 / 金美京 / 孔敏晶 / 朴成妍 / 李凤莲 / 金圣喆 / 李乌 / 李海云 / 孙成灿 / 金正英 / 李娜云 / 禹志贤 / 韩国 / 金度英 / 118分钟 / 82年生的金智英 / 剧情 / 刘英雅 Yeong-ah Yoo / 赵南珠 Nam-joo",
                title5:"2019-11-08(西班牙) / 2019-11-08(英国) / J·K·西蒙斯 / 詹森·舒瓦兹曼 / 拉什达·琼斯 / 琼·库萨克 / 诺曼·麦克唐纳徳 / 威尔·萨索 / 塞尔希奥·巴勃罗斯 / 米拉·布雷纳 / 内达·玛格丽特·拉巴 / 悉尼·布朗 / 泰迪·布鲁姆 / 艾玛·香农 / 肯德尔·卓依",
                title6:"2019-09-27(纽约电影节) / 2019-11-01(美国点映) / 2019-11-27(美国网络) / 罗伯特·德尼罗 / 阿尔·帕西诺 / 乔·佩西 / 安娜·帕奎因 / 杰西·普莱蒙 / 哈威·凯特尔 / 斯蒂芬·格拉汉姆 / 鲍比·坎纳瓦尔 / 杰克·休斯顿 / 阿莱卡萨·帕拉迪诺 / 凯瑟琳·纳杜奇",
                title7:"2019-11-08(西班牙) / 2019-11-08(英国) / J·K·西蒙斯 / 詹森·舒瓦兹曼 / 拉什达·琼斯 / 琼·库萨克 / 诺曼·麦克唐纳徳 / 威尔·萨索 / 塞尔希奥·巴勃罗斯 / 米拉·布雷纳 / 内达·玛格丽特·拉巴 / 悉尼·布朗 / 泰迪·布鲁姆 / 艾玛·香农 / 肯德尔·卓依... ",
                title8:"2019-08-21(美国) / 萨玛拉·维文 / 安迪·麦克道威尔 / 马克·奥布莱恩 / 亚当·布罗迪 / 亨利·科泽尼 / 妮基·瓜达尼 / 梅兰妮·斯科洛凡诺 / 克里斯蒂安·布鲁恩 / 伊利斯 莱韦斯克 / 约翰·拉尔斯顿 / 达妮埃拉·巴博萨 / 伊拉娜·盖尔",
                value1: 4.8,
                value2: 3.8,
                value3: 4.6,
                value4: 4.4,
                value5: 3.8,
                value6: 4.2,
                value7: 4.5,
                value8: 3.6,

            }
        }
    }
</script>

<style>

    #a{
        width: 1040px;
        width: 950px;
        margin: 0 auto;
        padding: 0;

    }
    .b{
        margin: auto;
        width: 500px;
        text-align:left;

    }
    .c{
        width:300px;
        padding-top: 30px;
        margin-left:63px;
        float:left;
        height:10px;
        display:inline-block;
    }

</style>