<template>
  <div>
    <div style="" class="zx-box">
      <!-- <img src="/images/zximg-1.jpg" alt="" /> -->
      <div class="bg-img"></div>

      <div class="main-box">
        <div class="left-box">
          <ul>
            <li>
              <h3>统计分析</h3>
            </li>
            <li>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-window-fullscreen"
                viewBox="0 1 16 16">
                <path
                  d="M3 3.5a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0Zm1.5 0a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0Zm1 .5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1Z" />
                <path
                  d="M.5 1a.5.5 0 0 0-.5.5v13a.5.5 0 0 0 .5.5h15a.5.5 0 0 0 .5-.5v-13a.5.5 0 0 0-.5-.5H.5ZM1 5V2h14v3H1Zm0 1h14v8H1V6Z" />
              </svg>
              农产品数据库
              <span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-chevron-right"
                  viewBox="0 0 16 16">
                  <path
                    fill-rule="evenodd"
                    d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z" />
                </svg>
              </span>
            </li>
            <li>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-window-fullscreen"
                viewBox="0 1 16 16">
                <path
                  d="M3 3.5a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0Zm1.5 0a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0Zm1 .5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1Z" />
                <path
                  d="M.5 1a.5.5 0 0 0-.5.5v13a.5.5 0 0 0 .5.5h15a.5.5 0 0 0 .5-.5v-13a.5.5 0 0 0-.5-.5H.5ZM1 5V2h14v3H1Zm0 1h14v8H1V6Z" />
              </svg>
              销售数据库
              <span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-chevron-right"
                  viewBox="0 0 16 16">
                  <path
                    fill-rule="evenodd"
                    d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z" />
                </svg>
              </span>
            </li>
          </ul>
          <div class="contact">
            <h5>联系我们</h5>
            <p>地址：安徽省淮南市寿县公共服务中心</p>
            <p>电话：0558-4820099</p>
            <p>邮编：236500</p>
          </div>
        </div>
        <div class="right-box">
          <div class="top-box">
            <h5>统计分析</h5>
            <p @click="goHome()">
              主页
              <span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-chevron-right"
                  viewBox="0 0 16 16">
                  <path
                    fill-rule="evenodd"
                    d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z" />
                </svg>
              </span>
            </p>
          </div>

          <div class="news-box">
            <ul class="ul-box">
              <li>
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-layout-text-sidebar-reverse"
                    viewBox="0 0 16 16">
                    <path
                      d="M12.5 3a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5zm0 3a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5zm.5 3.5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 .5-.5zm-.5 2.5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5z" />
                    <path
                      d="M16 2a2 2 0 0 0-2-2H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2zM4 1v14H2a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h2zm1 0h9a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5V1z" />
                  </svg>
                </span>
                <span>2022-04-27</span>
                寿县公共服务中心6月份入驻企业考核表
              </li>
              <li>
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-layout-text-sidebar-reverse"
                    viewBox="0 0 16 16">
                    <path
                      d="M12.5 3a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5zm0 3a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5zm.5 3.5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 .5-.5zm-.5 2.5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5z" />
                    <path
                      d="M16 2a2 2 0 0 0-2-2H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2zM4 1v14H2a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h2zm1 0h9a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5V1z" />
                  </svg>
                </span>
                <span>2022-04-27</span>
                寿县公共服务中心入驻企业6月份考核表
              </li>
              <li>
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-layout-text-sidebar-reverse"
                    viewBox="0 0 16 16">
                    <path
                      d="M12.5 3a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5zm0 3a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5zm.5 3.5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h5a.5.5 0 0 0 .5-.5zm-.5 2.5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h5z" />
                    <path
                      d="M16 2a2 2 0 0 0-2-2H2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2zM4 1v14H2a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h2zm1 0h9a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H5V1z" />
                  </svg>
                </span>
                <span>2022-04-27</span>
                打造“e品寿州”区域公共品牌，助力企业高质量发展
              </li>

              <!-- <li>12</li> -->
            </ul>
            <div class="paging">
              <nav aria-label="...">
                <ul class="pagination justify-content-center">
                  <li class="page-item disabled">
                    <a class="page-link">上一页</a>
                  </li>
                  <li class="page-item">
                    <a class="page-link" href="#">1</a>
                  </li>
                  <li class="page-item active" aria-current="page">
                    <a class="page-link" href="#">2</a>
                  </li>
                  <li class="page-item">
                    <a class="page-link" href="#">3</a>
                  </li>
                  <li class="page-item">
                    <a class="page-link" href="#">下一页</a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    data() {
      return {};
    },
    methods: {
      goHome() {
        this.$router.push("/");
      },
    },
  };
</script>
<style lang="scss" scoped>
  .zx-box {
    // height: 1000px;
    .bg-img {
      width: 100%;
      height: 260px;
      background-image: url(/images/zximg-1.jpg);
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
    }
    .main-box {
      display: flex;
      margin-top: 50px;
      padding: 0 50px;
      .left-box {
        width: 247px;
        // height: 600px;
        // border: 1px solid gray;
        ul {
          // border: 1px solid gray;
          box-shadow: 0px 0px 1px gray;
          width: 100%;
          padding: 0;
          list-style: none;
          text-align: center;
          li {
            width: 100%;
            height: 76px;
            line-height: 76px;
            border-bottom: 1px solid rgb(233, 222, 222, 0.3);
            &:not(:first-child) {
              cursor: pointer;
              &:hover {
                background: rgb(247, 234, 234);
              }
            }
            &:first-child {
              background: rgb(40, 151, 57);
              color: white;

              h3 {
                height: 76px;
                line-height: 76px;
              }
            }
            span {
              margin: 0 10px;
            }
          }
        }
        .contact {
          box-shadow: 0px 0px 1px gray;

          h5 {
            padding: 10px;
            text-align: center;
            background: rgb(40, 151, 57);
            color: white;
          }
          p {
            padding: 3px;
            margin: 0 0 10px;
          }
        }
      }
      .right-box {
        margin-left: 50px;
        width: 100%;
        box-shadow: 0px 0px 1px gray;
        margin-bottom: 20px;
        .top-box {
          padding: 30px;
          display: flex;
          justify-content: space-between;
          border-bottom: 1px solid rgb(233, 222, 222);
          p {
            cursor: pointer;
          }
          h5 {
            position: relative;
            color: rgb(40, 151, 57);
            &::after {
              position: absolute;
              content: "";
              display: block;
              bottom: -38px;
              left: 0px;
              width: 89px;
              height: 2px;
              background-color: rgb(40, 151, 57);
            }
          }
        }
        .news-box {
          .ul-box {
            list-style: none;
            padding: 0;
            li {
              padding: 0 20px;
              height: 60px;
              border-bottom: 1px solid rgb(233, 222, 222);
              line-height: 60px;
              &:last-child {
                // border: none;
              }

              cursor: pointer;
              &:hover {
                background: rgb(248, 248, 248);
              }
              span {
                margin: 0 10px;
              }
            }
          }
        }
      }
    }
  }
  @media only screen and (max-width: 450px) {
  }
</style>
