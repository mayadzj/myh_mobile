<template>
    <div id="apply">
      <div class="xinxi-kong"></div>
      <!-- 内容 -->
      <nav class="yuyue-content clear">
        <!-- 切换 -->
        <div class="con-head">
          <div class="con-wap">
            <div><span>进行中的活动</span></div>
            <div><span>已结束的活动</span></div>
          </div>
        </div>
        <div class="con-del">
          <div class="del-middle clear">
            <p>取消</p>
            <p>删除</p>
            <p>全选</p>
          </div>
        </div>
        <!-- 浏览结果 -->
        <div class="con-nav clear">
          <div class="nav-middle">
            <div class="nav-top clear">
              <p>承德市 御道庄园小区</p>
              <p>已报名110人</p>
            </div>
            <div class="nav-bottom clear">
              <div class="bot-pic">
                <img src="../assets/images/my/fangyuan2.png" alt="">
              </div>
              <div class="bot-zi">
                <p>集合地址：北京市顺义区南法信地铁站</p>
                <p>看房电话：<span>176-1011-0111</span></p>
                <p>预约时间：2016.05.03—08:43:12</p>
                <p>集合时间：2016.05.03—08:43:12</p>
              </div>
            </div>
          </div>
        </div>

        <!-- 浏览结果 -->
        <div class="con-nav clear">
          <div class="nav-middle nav-right">
            <div class="nav-top clear">
              <p>承德市 御道庄园小区</p>
              <p>已报名110人</p>
            </div>
            <div class="nav-bottom clear">
              <div class="bot-pic">
                <img src="../assets/images/my/fangyuan2.png" alt="">
              </div>
              <div class="bot-zi">
                <p>集合地址：北京市顺义区南法信地铁站</p>
                <p>看房电话：<span>176-1011-0111</span></p>
                <p>预约时间：2016.05.03—08:43:12</p>
                <p>集合时间：2016.05.03—08:43:12</p>
              </div>
            </div>
          </div>
          <div class="nav-xuan">
            
          </div>
        </div>
        <!-- <div class="xinxi-kong"></div> -->
      </nav>
    </div>
</template>

<script>
export default {
  name: 'apply',
  // data () {
  //   houselist: {}
  // },
  // mounted () {
  //   this.myhouse()
  // },
  // methods: {
  //   myhouse  () {
  //     var infos = {
  //       type: 1
  //     }
  //     this.$http.post(myHost + 'myh_web/viewHouseInfo',infos).then((response) => {
  //       var data = response.data
  //       data = data.resultBean
  //       data = data.object
  //       data = data.list
  //       this.houselist = data
  //     })
  //   }
  // }
};
</script>

<style scoped>
  .yuyue-content{
    margin-top: 0;
  }
</style>
