<template>
  <div className="foot">
    <div className="footbox">
      <img className='dblogo'
      src='../assets/code/2.png' alt="" />
      <div className="dbcen">
        <div className="dbtitle">有问题 律师帮</div>
        <p>发布咨询问题，匹配专业律师解答</p>
        <p>选择在线律师，直接电话沟通解决</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">

.foot {
  width           : 100%;
  height          : 250px;
  background-color: #1080f8;
  padding-top     : 50px;

  .footbox {
    width          : 500px;
    margin         : 0 auto;
    display        : flex;
    align-items    : center;
    justify-content: space-between;
    text-align     : center;

    .dblogo {
      width : 133px;
      height: 133px;
    }

    .dbcen {
      .dbtitle {
        font-size     : 30px;
        font-family   : Source Han Sans CN, Source Han Sans CN-Medium;
        font-weight   : 500;
        text-align    : center;
        color         : #ffffff;
        letter-spacing: 0.96px;
      }

      p {
        font-size     : 20px;
        font-family   : Source Han Sans CN, Source Han Sans CN-Medium;
        font-weight   : 500;
        text-align    : center;
        color         : #ffffff;
        letter-spacing: 0.51px;
      }
    }

  }

}
</style>
