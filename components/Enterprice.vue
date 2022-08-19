<template>
  <div class="box container">
    <div class="top-title">
      <h2>农业品牌</h2>
      <p>查看更多...</p>
    </div>
    <!-- <div class="produce-box"> -->
    <ul class="ul-box row">
      <li class="col-12 col-xl-3">
        <img src="/images/sxyou.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxyou.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxyou.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxyou.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
        <p>寿县2021年“中国农民丰收节”成功举办寿县2021年“中国寿县2021年“中国农民丰收节”成功举办</p>
      </li>
    </ul>
  </div>
  <!-- </div> -->
</template>

<script>
  export default {};
</script>

<style lang="scss" scoped>
  .box {
    .top-title {
      padding: 20px;
      display: flex;
      margin: 0 0 20px;
      h2 {
        font-weight: bold;
        padding-left: 10px;
        border-left: 5px solid green;
      }
      p {
        margin: 10px 0 0 50px;
      }
    }
    .ul-box {
      padding: 0;
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      li {
        cursor: pointer;
        width: 275px;
        // box-shadow: 0 0 2px rgba(41, 40, 40, 0.9);
        position: relative;
        margin-bottom: 30px;
        list-style: none;
        p {
          margin-top: 20px;
          overflow: hidden;
          text-overflow: ellipsis;
          display: -webkit-box;
          -webkit-line-clamp: 2;
          -webkit-box-orient: vertical;
        }
        img {
          width: 100%;
          height: 260px;
        }
      }
    }
  }
</style>
