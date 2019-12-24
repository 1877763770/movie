<template>
    <div style="float:left;margin-left:0px">
        <h1 style="text-align: left">豆瓣电影排行榜</h1>
        <h2 style="color:green;text-align: left">豆瓣新片榜......</h2>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
                <el-row>
                    <el-col :span="5">
                        <img src="../assets/6.jpg" style="width:150px;height: 220px">
                    </el-col>
                    <el-col :span="8" style="text-align:left">
                            <div class="name" style="color:dodgerblue">
                                <a >爱尔兰人
                                    / <span style="font-size:13px;">爱尔兰杀手(港) / 听说你刷房子了</span>
                                </a>
                            </div>

                        <p class="pl">2019-09-27(纽约电影节) / 2019-11-01(美国点映) / 2019-11-27(美国网络) / 罗伯特·德尼罗 / 阿尔·帕西诺 / 乔·佩西 / 安娜·帕奎因 / 杰西·普莱蒙 / 哈威·凯特尔 / 斯蒂芬·格拉汉姆 / 鲍比·坎纳瓦尔 / 杰克·休斯顿 / 阿莱卡萨·帕拉迪诺 / 凯瑟琳·纳杜奇...</p>
                        <div style="display: inline-block">
                            <el-rate disabled  v-model="movie.scoring.star"></el-rate>
                        </div>
                        <div style="margin-top:-21px;argin-left:120px;margin-left:130px">
                            <a style="color:#b88b1f">9.1</a>
                            &nbsp;(123358人评价）
                        </div>
                    </el-col>

                </el-row>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
                    <el-row>
                        <el-col :span="5">
                            <img src="../assets/1.jpg" style="width:150px;height: 220px">
                        </el-col>
                        <el-col :span="8" style="text-align:left">
                            <td>
                                <div class="name" style="color:dodgerblue">
                                    <a>小丑
                                        / <span style="font-size:13px;">小丑起源电影：罗密欧 / Romeo</span>
                                    </a>
                                </div>
                            </td>
                            <p class="pl">2019-08-31(威尼斯电影节) / 2019-10-04(美国) / 杰昆·菲尼克斯 / 罗伯特·德尼罗 / 马克·马龙 / 莎姬·贝兹 / 谢伊·惠格姆 / 弗兰西丝·康罗伊 / 布莱恩·考伦 / 布莱恩·泰里·亨利 / 布莱特·卡伦 / 道格拉斯·霍奇斯 / 格伦·弗莱施勒 / 比尔·坎普...</p>
                            <div style="display: inline-block">
                                <el-rate disabled  v-model="movie.scoring.star"></el-rate>
                            </div>
                            <div style="margin-top:-21px;argin-left:120px;margin-left:130px">
                                <a style="color:#b88b1f">8.8</a>
                                &nbsp;(380752人评价）
                            </div>
                        </el-col>
                    </el-row>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
                        <el-row>
                            <el-col :span="5">
                                <img src="../assets/9.jpg" style="width:150px;height: 220px">
                            </el-col>
                            <el-col :span="8" style="text-align:left">
                                <td>
                                    <div class="name" style="color:dodgerblue">
                                        <a>82年生的金智英
                                            / <span style="font-size:13px;">82年生金智英 / Kim Ji-young,Born 1982</span>
                                        </a>
                                    </div>
                                </td>
                                <p class="pl">2019-10-23(韩国) / 2019-11-07(中国香港) / 郑有美 / 孔侑 / 金美京 / 孔敏晶 / 朴成妍 / 李凤莲 / 金圣喆 / 李乌 / 李海云 / 孙成灿 / 金正英 / 李娜云 / 禹志贤 / 韩国 / 金度英 / 118分钟 / 82年生的金智英 / 剧情 / 刘英雅 Yeong-ah Yoo / 赵南珠 Nam-joo...</p>
                                <div style="display: inline-block">
                                    <el-rate disabled  v-model="movie.scoring.star"></el-rate>
                                </div>
                                <div style="margin-top:-21px;argin-left:120px;margin-left:130px">
                                    <a style="color:#b88b1f">8.7</a>
                                    &nbsp;39141人评价）
                                </div>
                            </el-col>
                        </el-row>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
                            <el-row>
                                <el-col :span="5">
                                    <img src="../assets/2.jpg" style="width:150px;height: 220px">
                                </el-col>
                                <el-col :span="8" style="text-align:left">
                                    <td>
                                        <div class="name" style="color:dodgerblue">
                                            <a>好莱坞往事
                                                / <span style="font-size:13px;">从前，有个荷里活(港) / 从前，有个好莱坞...(台)</span>
                                            </a>
                                        </div>
                                    </td>
                                    <p class="pl">2019-05-21(戛纳电影节) / 2019-07-26(美国) / 2019(中国大陆) / 莱昂纳多·迪卡普里奥 / 布拉德·皮特 / 玛格特·罗比 / 埃米尔·赫斯基 / 玛格丽特·库里 / 蒂莫西·奥利芬特 / 茱莉亚·巴特斯 / 奥斯汀·巴特勒 / 达科塔·范宁 / 布鲁斯·邓恩 /...</p>
                                    <div style="display: inline-block">
                                        <el-rate disabled  v-model="movie.scoring.star"></el-rate>
                                    </div>
                                    <div style="margin-top:-21px;argin-left:120px;margin-left:130px">
                                        <a style="color:#b88b1f">7.3</a>
                                        &nbsp;(74616人评价）
                                    </div>
                                </el-col>
                            </el-row>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
                                <el-row>
                                    <el-col :span="5">
                                        <img src="../assets/3.jpg" style="width:150px;height: 220px">
                                    </el-col>
                                    <el-col :span="8" style="text-align:left">
                                        <td>
                                            <div class="name" style="color:dodgerblue">
                                                <a>婚姻故事</a>
                                            </div>
                                        </td>
                                        <p class="pl">2019-08-29(威尼斯电影节) / 2019-12-06(美国) / 斯嘉丽·约翰逊 / 亚当·德赖弗 / 梅里特·韦弗 / 劳拉·邓恩 / 雷·利奥塔 / 朱丽·哈基提 / 马克·奥布莱恩 / 华莱士·肖恩 / 阿伦·阿尔达 / 凯尔·柏海莫 / 米奇·萨姆纳 / 艾奇·罗伯逊 / 马修·马希尔...</p>
                                        <div style="display: inline-block">
                                            <el-rate disabled  v-model="movie.scoring.star"></el-rate>
                                        </div>
                                        <div style="margin-top:-21px;argin-left:120px;margin-left:130px">
                                            <a style="color:#b88b1f">8.8</a>
                                            &nbsp;(26709人评价）
                                        </div>
                                    </el-col>
                                </el-row>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
                                    <el-row>
                                        <el-col :span="5">
                                            <img src="../assets/4.jpg" style="width:150px;height: 220px">
                                        </el-col>
                                        <el-col :span="8" style="text-align:left">
                                            <td>
                                                <div class="name" style="color:dodgerblue">
                                                    <a>  准备好了没
                                                        / <span style="font-size:13px;">弑婚游戏(台) / 爆血新婚夜(港)</span>
                                                    </a>
                                                </div>
                                            </td>
                                            <p class="pl">2019-08-21(美国) / 萨玛拉·维文 / 安迪·麦克道威尔 / 马克·奥布莱恩 / 亚当·布罗迪 / 亨利·科泽尼 / 妮基·瓜达尼 / 梅兰妮·斯科洛凡诺 / 克里斯蒂安·布鲁恩 / 伊利斯 莱韦斯克 / 约翰·拉尔斯顿 / 达妮埃拉·巴博萨 / 伊拉娜·盖尔 /...</p>
                                            <div style="display: inline-block">
                                                <el-rate disabled  v-model="movie.scoring.star"></el-rate>
                                            </div>
                                            <div style="margin-top:-21px;argin-left:120px;margin-left:130px">
                                                <a style="color:#b88b1f">8.8</a>
                                                &nbsp;(123358人评价）
                                            </div>
                                        </el-col>
                                    </el-row>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
                                        <el-row>
                                            <el-col :span="5">
                                                <img src="../assets/7.jpg" style="width:150px;height: 220px">
                                            </el-col>
                                            <el-col :span="8" style="text-align:left">
                                                <td>
                                                    <div class="name" style="color:dodgerblue">
                                                        <a>克劳斯：圣诞节的秘密
                                                            / <span style="font-size:13px;">圣诞老人</span>
                                                        </a>
                                                    </div>
                                                </td>
                                                <p class="pl">2019-11-08(西班牙) / 2019-11-08(英国) / J·K·西蒙斯 / 詹森·舒瓦兹曼 / 拉什达·琼斯 / 琼·库萨克 / 诺曼·麦克唐纳徳 / 威尔·萨索 / 塞尔希奥·巴勃罗斯 / 米拉·布雷纳 / 内达·玛格丽特·拉巴 / 悉尼·布朗 / 泰迪·布鲁姆 / 艾玛·香农 / 肯德尔·卓依...</p>
                                                <div style="display: inline-block">
                                                    <el-rate disabled  v-model="movie.scoring.star"></el-rate>
                                                </div>
                                                <div style="margin-top:-21px;argin-left:120px;margin-left:130px">
                                                    <a style="color:#b88b1f">8.8</a>
                                                    &nbsp;(123358人评价.）
                                                </div>
                                            </el-col>

        </el-row>
        <div>
            <hr style="border:1px dashed;color:darkgray;width:900px;margin-left:0px"/>
        </div>
    </div>
</template>
<script>
    export default{
        data: function () {
            return {
                movie: {
                    scoring: {
                        star: 4.5
                    }

                }
            }
        }
    }

 </script>
