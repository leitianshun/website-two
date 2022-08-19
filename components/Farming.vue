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
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxyou.png" alt="" />
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxyou.png" alt="" />
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxyou.png" alt="" />
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
      </li>
      <li class="col-12 col-xl-3">
        <img src="/images/sxmiantiao.png" alt="" />
      </li>
    </ul>
    <hr />
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
        box-shadow: 0 0 2px rgba(41, 40, 40, 0.9);
        position: relative;
        margin-bottom: 30px;
        list-style: none;
        padding: 0;
        img {
          width: 100%;
          height: 260px;
        }
      }
    }
  }
  @media only screen and (max-width: 450px) {
  }
</style>
