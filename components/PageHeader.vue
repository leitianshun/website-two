<!-- Please remove this file from your project -->
<template>
  <div class="contain" style="">
    <div class="bgImg">
      <img src="/images/epsz.png" alt="" />
      <h3>
        寿县电子商务公共服务中心
        <h6 class="colorToggle">Shouxian Rural E-Commerce Public Service Center</h6>
      </h3>
      <!-- <img src="/images/sx.jpg" alt="" /> -->
    </div>
    <nav class="navbar-expand-lg navbar-light bg-light navs">
      <div class="list">
        <ul class="items">
          <li class="nav-item">
            <nuxt-link active-class="active" to="/" exact class="nav-link">首页</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" to="/information" class="nav-link">寿县资讯</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" to="/unique" class="nav-link">寿县特色</nuxt-link>
          </li>
          <li class="nav-item">
            <!-- :to="{ path: '/news', query: { pageNum: 1 } }" -->

            <nuxt-link active-class="active" to="/server" class="nav-link">电商服务</nuxt-link>
          </li>

          <li class="nav-item">
            <nuxt-link active-class="active" to="analyse" class="nav-link">分析统计</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" to="produce" class="nav-link">农产品追溯</nuxt-link>
          </li>
        </ul>
      </div>
    </nav>

    <div class="mobile">
      <div class="header">
        <a href="/">
          <!-- <img
            :src="`${cdnUrl}/images/dxsqtext.png`"
            style="width: 100px; height: 30px"
            alt="dxsq"
          /> -->
        </a>
        <span class="iconfont open" @click="(active = true), (isShow = true)">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="25"
            height="25"
            fill="currentColor"
            class="bi bi-list"
            viewBox="0 0 16 16">
            <path
              fill-rule="evenodd"
              d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z" />
          </svg>
        </span>
      </div>

      <div v-if="active" class="menu">
        <div class="silder-bar">
          <div class="menu-header" style="">
            <!-- <img :src="`${cdnUrl}/images/dxsqtext.png`" style="width: 150px; height: 40px; color: white" alt="" /> -->
            <div class="iconfont close" @click="active = false">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="25"
                height="25"
                fill="currentColor"
                class="bi bi-x-lg"
                viewBox="0 0 16 16">
                <path
                  d="M2.146 2.854a.5.5 0 1 1 .708-.708L8 7.293l5.146-5.147a.5.5 0 0 1 .708.708L8.707 8l5.147 5.146a.5.5 0 0 1-.708.708L8 8.707l-5.146 5.147a.5.5 0 0 1-.708-.708L7.293 8 2.146 2.854Z" />
              </svg>
            </div>
          </div>
          <ul class="menu-list">
            <li class="nav-item" @click="active = false">
              <nuxt-link to="/" class="nav-link">首页</nuxt-link>
            </li>
            <li class="nav-item" @click="active = false">
              <nuxt-link active-class="active" to="/information" class="nav-link">寿县资讯</nuxt-link>
            </li>
            <li class="nav-item" @click="active = false">
              <nuxt-link active-class="active" to="/unique" class="nav-link">寿县特色</nuxt-link>
            </li>
            <li class="nav-item" @click="active = false">
              <!-- <nuxt-link :to="{ path: '/news', query: { pageNum: 1 } }" class="nav-link">行业新闻</nuxt-link> -->
              <nuxt-link active-class="active" to="/server" class="nav-link">电商服务</nuxt-link>
            </li>
            <li class="nav-item" @click="active = false">
              <nuxt-link active-class="active" to="analyse" class="nav-link">分析统计</nuxt-link>
            </li>
            <li class="nav-item" @click="active = false">
              <nuxt-link active-class="active" to="analyse" class="nav-link">分析统计</nuxt-link>
            </li>
            <li class="nav-item" @click="active = false">
              <nuxt-link active-class="active" to="produce" class="nav-link">农产品追溯</nuxt-link>
            </li>
          </ul>
        </div>
        <div style="color: white; padding: 0 20px; text-align: left">
          <span>
            <i style="margin-right: 10px">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-telephone-fill"
                viewBox="0 0 16 16">
                <path
                  fill-rule="evenodd"
                  d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z" />
              </svg>
            </i>
            0556-4629268
          </span>
          <div style="margin-top: 10px">
            <hr />
            <span>
              <i style="margin-right: 10px">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-geo-alt"
                  viewBox="0 0 16 16">
                  <path
                    d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z" />
                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z" />
                </svg>
              </i>
              安徽省安庆市怀宁县江镇镇新联村
            </span>
          </div>
          <hr />
          <div>
            <p>版权所有：怀宁县大雄山泉水开发有限公司</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  // import { cdnUrl } from '../common/setting'

  export default {
    name: "PageHeader",
    data() {
      return {
        active: false,
        isShow: false,
      };
    },

    methods: {},
  };
</script>

<style lang="scss" scoped>
  .contain {
    border-bottom: 1px solid gray;
    position: sticky;
    top: 0;
    width: 100%;
    height: auto;
    z-index: 99;
    .bgImg {
      background-image: url(/images/sx.jpg);
      width: 100%;
      height: 180px;
      background-repeat: no-repeat;
      background-size: cover;
      background-position: center center;
      color: white;
      display: flex;
      align-items: center;
      padding-left: 50px;
      .colorToggle {
        color: white;
        animation: colorToggle 2.5s ease-in-out infinite alternate;
        @keyframes colorToggle {
          0% {
            color: rgba(236, 232, 232, 0.8);
          }
          30% {
            color: rgba(127, 245, 162, 0.6);
          }
          50% {
            color: rgba(108, 236, 91, 0.8);
          }
          80% {
            color: rgba(174, 245, 174, 0.8);
          }
          100% {
            color: rgb(40, 151, 57, 1);
          }
        }
      }
    }
    .navs {
      width: 100%;
      // height: 50px;
      .list {
        background: rgb(40, 151, 57);
        width: 100%;
        height: 50px;

        .items {
          // background-color: beige;
          list-style: none;
          display: flex;
          justify-content: space-around;
          align-items: center;
          padding: 0 30px 0;
          margin: 0;
          height: 100%;
          .active {
            color: rgb(0, 235, 0);
          }
          li {
            cursor: pointer;
            a {
              color: white;
              margin: 0 22px;
              transition: all 0.6s;
              position: relative;
              @keyframes change {
                0% {
                  color: rgba(241, 243, 144, 0.6);
                }
                30% {
                  color: rgba(156, 243, 116, 0.8);
                }
                50% {
                  color: rgba(153, 240, 142, 0.5);
                }
                80% {
                  color: rgba(174, 224, 109, 0.8);
                }
                100% {
                  color: rgb(87, 247, 12);
                }
              }
              &:hover {
                animation: change 1.5s linear 0s infinite;
              }
              &:hover {
                background-color: rgb(253, 168, 71);
                transform: scale(1.2);
              }
              // &:focus {
              //   color: rgb(235, 97, 0);
              // }
              &::after {
                content: "";
                position: absolute;
                // top: 0;
                left: 5px;
                right: 0;
                bottom: 5px;
                height: 2px;
                width: 0;
                background-color: rgb(177, 247, 86);
                transition: all 1s;
                @keyframes width {
                  0% {
                    width: 0;
                  }
                  30% {
                    width: 30%;
                  }
                  50% {
                    width: 50%;
                  }
                  80% {
                    width: 80%;
                  }
                  100% {
                    width: calc(100% - 10px);
                  }
                }
              }
              &:hover::after {
                // width: calc(100% - 10px);
                animation: width 1s linear 0s infinite alternate;
              }
            }
          }
        }
      }
    }
    .mobile {
      display: none;
    }
  }
  @media only screen and (max-width: 450px) {
    .contain {
      width: 100%;
      position: sticky;
      top: -1px;
      // height: 50px;
      // z-index: 10;
      // .navs {
      //   .list {
      //     .items {
      //       // display: none;
      //       // border: 1px solid red;
      //     }
      //   }
      // }
      .navs {
        width: 100%;
        display: none;
      }
      .mobile {
        // position: fixed;
        // top: 0;
        // left: 0;
        // width: 100%;
        // z-index: 999;
        // border-bottom: 1px solid rgb(161, 160, 160);
        // background-color: white;
        display: block;

        .header {
          width: 100%;
          height: 40px;
          background: rgb(72, 153, 74);
        }

        // img {
        //   margin: 10px;
        // }
        .open {
          float: right;
          width: 50px;
          height: 100%;
          color: white;
          // margin: 1px 50px;
          font-size: 25px;
          // line-height: 50px;
          // font-weight: bold;
          // width: 20px;
        }

        .menu {
          width: 240px;
          // border: 1px solid red;
          height: 100%;
          position: fixed;
          left: 0;
          top: 0;
          z-index: 20;
          background-color: rgb(142, 206, 82);
          // opacity: 1;
          transform: translateX(0);
          // visibility: visible;
          transition: all 0.9s;
          // position: relative;
          // &::after {
          //   content: "";

          //   position: absolute;
          //   top: 0;
          //   left: 0;
          //   right: 0;
          //   bottom: 0;
          //   background-color: #000000;
          //   opacity: 0.5;
          // }
          .silder-bar {
            padding: 30px 0 0;
            // .menu-header {
            //   // width: 400px;
            //   padding: 0 10px;
            // }
            .close {
              float: right;
              width: 40px;
              font-size: 35px;
              // margin: 10px 30px;
              color: white;
              font-weight: 1000px;
              svg {
              }
            }
            .menu-list {
              list-style: none;
              padding: 0;
              margin-top: 30px;
              text-align: center;
              .nav-item {
                .nav-link {
                  color: white;
                  border-bottom: 1px solid rgba(255, 255, 255, 0.8);
                  height: 50px;
                  // line-height: 50px;
                }
              }
            }
          }
        }
      }
    }
  }
  // @media only screen and (max-width: 375px) {
  //   .mobile {
  //     .menu {
  //       .menu-header {
  //         width: 350px;
  //       }
  //     }
  //   }
  // }
  @media only screen and (min-width: 1850px) {
    .contain {
      .navs {
        .nav-items {
          margin-left: 246px;
        }
      }
    }
  }
</style>
