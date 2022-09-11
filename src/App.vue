<template>
  <div id="app">
    <div class="index">
      <div class="header">
        <span>首页</span>
        <span>引言</span>
        <span>Z世代的异宠热</span>
        <span>陷入孤岛的困境</span>
        <span>互相伤害后的伤痛</span>
        <span>尾声</span>
      </div>
      <div class="opcity-container">
        <div class="fix-nail"></div>
        <div class="title-words title-words1">异宠热袭来: </div>
        <div class="title-words title-words2">真正的爱是生命对生命的</div>
      </div>
    </div>
    <div class="introduction">
      <div class="section-title">
        <div class="title-words">引言</div>
        <div class="title-border"></div>
        <div class="opcity-container-words">
          <div class="fix-nail"></div>
          <div class="introduction-words">
            从王校长的柯尔鸭、羊驼萌翻网友，到今天社交网站大火的暹罗鳄饲养日常，
            <span class="introduction-special-words">宠物经济疯狂, Z世代下的异宠热正急剧升温</span>, 人类已不止于弧化饲养猫狗, 而是在 “另类”宠
            物的饲养中寻找新的满足感。当一众人饲养异宠如痴如醉时，总会传来不解、讽刺甚至谩骂
            的声音。“因为爬宠很炫酷、养起来很简单他们的品种非常多样，更出于对这些动物的喜
            爱”
            “蛇和那些爬行动物的花纹难以接受，看见就会恶心”
            “这不就是些五毒四害”
            “冷血
            动物没有感情” “这些都是在野生动物饲养会有很大危害〞这些都是网民就异宠话题的讨
            论。喜爱异宠的人可能只有一个理由而庆恶它们的人可能有千万个理由。在异宠热的持续冲
            击下，应该接受还是抗拒，应该表达喜爱还是厌恶？面对这些疑问，
            <span class="introduction-special-words">此篇无意行走在“爱恨”恨”之间，而是把这些感受放到一边，先去了解，深刻的了解便是一切的基础。</span>
          </div>
        </div>
      </div>
    </div>
    <div class="image-container">
      <el-row :gutter="30" style="padding:0 20px; margin: 20px 0;">
        <el-col :span="6"  v-for="(item, index) in imageArr1" class="image-item-card-col">
          <el-card :body-style="{ padding: '0px' }" class="image-item-card">
            <img :src="item"
              class="image">
          </el-card>
        </el-col>
      </el-row>
      <el-row :gutter="30" style="padding:0 20px; margin: 20px 0;">
        <el-col :span="6"  v-for="(item, index) in imageArr2" class="image-item-card-col">
          <el-card :body-style="{ padding: '0px' }" class="image-item-card">
            <img :src="item"
              class="image">
          </el-card>
        </el-col>
      </el-row>
    </div>
    <div class="introduction">
      <div class="section-title">
        <div class="title-words">Z世代的异宠热</div>
        <div class="title-border"></div>
        <div class="opcity-container-words">
          <div class="fix-nail"></div>
          <div class="introduction-words">
            从王校长的柯尔鸭、羊驼萌翻网友，到今天社交网站大火的暹罗鳄饲养日常，
            <span class="introduction-special-words">宠物经济疯狂, Z世代下的异宠热正急剧升温</span>, 人类已不止于弧化饲养猫狗, 而是在 “另类”宠
            物的饲养中寻找新的满足感。当一众人饲养异宠如痴如醉时，总会传来不解、讽刺甚至谩骂
            的声音。“因为爬宠很炫酷、养起来很简单他们的品种非常多样，更出于对这些动物的喜
            爱”
            “蛇和那些爬行动物的花纹难以接受，看见就会恶心”
            “这不就是些五毒四害”
            “冷血
            动物没有感情” “这些都是在野生动物饲养会有很大危害〞这些都是网民就异宠话题的讨
            论。喜爱异宠的人可能只有一个理由而庆恶它们的人可能有千万个理由。在异宠热的持续冲
            击下，应该接受还是抗拒，应该表达喜爱还是厌恶？面对这些疑问，
            <span class="introduction-special-words">此篇无意行走在“爱恨”恨”之间，而是把这些感受放到一边，先去了解，深刻的了解便是一切的基础。</span>
          </div>
        </div>
      </div>
    </div>
    <div class="abs">
    </div>
  </div>
</template>

<script>
import indexPaper from './components/indexPaper.vue'

export default {
  name: 'App',
  components: {
    indexPaper
  },
  data() {
    return {
      mis: 'liaojie',
      value: '',
      imageArr1:[
        require('./assets/2.jpg'),
        require('./assets/3.jpg'),
        require('./assets/4.jpg'),
        require('./assets/5.jpg')
      ],
      imageArr2: [
        require('./assets/6.jpg'),
        require('./assets/7.jpg'),
        require('./assets/8.jpg'),
        require('./assets/9.jpg')
      ]
    }
  },
  method: {
    getMis() {
      console.log(this.mis)
      console.log("woshinibababa")
    }
  }
}
</script>
<style lang="less" src="./css/App.less">

</style>
