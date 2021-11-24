<template>
  <div class="box">
    <div class="header">
      <div class="lleft">
        <span>
          <img
            src="https://login.jiuxian.com/img/header/left.jpg?version=20160401"
            alt=""
          />
        </span>
        <a href="#">
          <img src="https://login.jiuxian.com/img/reg/slogan.jpg" alt="" />
        </a>
      </div>
      <div class="jx-head-nav">
        <div class="jx-head-icon">
          <span>帮助中心</span>
        </div>
      </div>
      <div class="jx-reg">
        <span>欢迎来到酒仙网</span>
        <a href="#"> 免费注册 </a>
      </div>
    </div>
    <div
      class="main"
      style="
        background: url(https://img10.jiuxian.com/bill/2021/0708/b2f01513f61d412abdadb8c162e83dee.jpg)
          no-repeat center top;
      "
    >
      <div class="jx-main">
        <div class="jx-contentbd">
          <div class="loginCon">
            <div class="loginTit">
              <a class="userLogin on">帐号登录</a>
              <span>|</span>
              <a class="mobileLogin">手机动态密码登录</a>
            </div>
            <div class="loginType"> 
              <input type="text" placeholder="用户名/邮箱/手机号" />
              <input type="text" placeholder="密码" />
              <input type="text" placeholder="验证码" />
              <div class="loginBtn">登录</div>
              <div class="moreChoice">
                <span>忘记密码</span>
                <span>免费注册</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="jx-foot">
        <p>
          © 酒仙网 2011 jiuxian.com All Rights Reserved 京ICP证110141号
          京公网安备1101050188221
        </p>
        <p class="red">
          购买前请确认达到法定饮酒年龄！酒仙网不销售任何含酒精产品给18岁以下人士！
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.box {
  width: 100%;
  .header {
    width: 1000px;
    height: 88px;
    margin: 0 auto;
    .lleft {
      width: 257px;
      height: 63px;
      float: left;
      margin-top: 15px;
      span {
        width: 140px;
        img {
          width: 140px;
          height: 63px;
        }
      }
      a {
        width: 117px;
        float: right;
        img {
          width: 110px;
          height: 63px;
          float: right;
        }
      }
    }
    .jx-head-nav {
      width: 77px;
      height: 14px;
      font-size: 12px;
      line-height: 14px;
      float: right;
      display: inline;
      margin: 48px 0 0 20px;
      position: relative;
      cursor: pointer;
      z-index: 10;
      .jx-head-icon {
        height: 14px;
        position: relative;
        z-index: 2;
        span {
          display: inline-block;
          color: #666;
          margin-right: 6px;
        }
      }
    }
    .jx-reg {
      float: right;
      color: #999;
      margin-top: 48px;
      height: 14px;
      line-height: 14px;
      font-size: 12px;

      a {
        margin-left: 20px;
      }
    }
  }
  .main {
    width: 100%;
    padding: 0 0 50px;
    height: 600px;
    margin-bottom: 50px;
    .jx-main {
      width: 1000px;
      margin: 0 auto;
      .jx-contentbd {
        background-color: #fff;
        overflow: hidden;
        position: relative;
        width: 350px;
        height: 405px;
        top: 100px;
        left: 650px;
        .loginCon {
          width: 270px;
          margin-left: 40px;
          .loginTit {
            margin: 14px 0 19px;
            height: 40px;
            overflow: hidden;
            line-height: 40px;
            border-bottom: 1px solid #e9e9e9;
            a.on {
              color: #e4393c;
              font-weight: bold;
            }
            a {
              font-size: 16px;
              float: left;
              color: #999;
            }
            span {
              font-size: 12px;
              color: #999;
              padding: 0 18px;
              float: left;
            }
          }
          .loginType {
            height: 267px;
            border-bottom: 1px dotted #ccc;
            overflow: hidden;
            input {
              width: 270px;
              height: 42px;
              margin-bottom: 20px;
            }
            .loginBtn {
              width: 270px;
              background-color: #e10303;
              height: 40px;
              color: #fff;
              border-radius: 2px;
              text-align: center;
              line-height: 40px;
              border: 0;
              cursor: pointer;
              font-family: "Microsoft Yahei";
              margin-bottom: 11px;
            }
            .moreChoice {
              width: 270px;
              height: 16px;
              margin-bottom: 16px;
              font-size: 12px;
              span {
                color: #999;
                display: inline-block;
                padding-left: 13px;
              }
            }
          }
        }
      }
    }
  }
  .footer {
    width: 100%;
    padding: 10px 0 0;
    .jx-foot {
      width: 1000px;
      height: 60px;
      font-size: 12px;
      margin: 0 auto;
      p {
        line-height: 30px;
        color: #333;
        text-align: center;
      }
      .red {
        line-height: 30px;
        color: #ff0000;
      }
    }
  }
}
</style>>

