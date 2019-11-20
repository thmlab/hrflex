<template>
  <div class="main">
    <div class="logo">弹一弹</div>
    <div class="search-form">
      <div class="search-form-inner">
        <input type="text" class="word" placeholder="请输入你要弹的人的名字..." />
        <a class="btn-submit" href="javascript:void(0);">
          <svg id="icon-search" viewBox="0 0 1036 1024">
            <path
              d="M1003.53408406 908.83318625l-83.16681468 83.16681375-203.84975344-200.87517375C644.5812575 847.15619094 555.22246156 881.87985312 456.93992656 881.87985312a424.93992656 424.93992656 0 1 1 424.93992656-424.93992656 421.66181906 421.66181906 0 0 1-82.98469687 250.22891156l204.63892781 201.66434813zM456.93992656 153.41140719a303.52851938 303.52851938 0 1 0 0.06070594 607.11774375A303.52851938 303.52851938 0 0 0 456.93992656 153.41140719z"
            />
          </svg>
        </a>
      </div>
    </div>
    <div class="tip">请求制定互联网事业部技术团队弹性工作制。 </div>
    <div class="copyright">第一健康版权所有 @2019</div>
  </div>
</template>

<style lang="less" scoped>
.main {
  width: 900px;
  margin: 0px auto;
  margin-top: 20vh;
  text-align: center;

  .logo {
    width: 100%;
    height: 100px;
    line-height: 100px;
    font-size: 65px;
    color: #333;
    font-weight: 100;
  }

  .search-form {
    position: relative;
    padding: 50px;
    padding-left: 100px;
    padding-right: 100px;
    box-sizing: border-box;
    width: 100%;

    .search-form-inner {
      box-sizing: border-box;
      position: relative;
      height: 60px;
      width: 100%;
      transition: all 0.3s ease;
      background-color: transparent;
      border-radius: 30px;
      background-color: #fff;

      input {
        outline: none;
        display: block;
        height: 100%;
        appearance: none;
        width: 100%;
        font-size: 18px; 
        font-family: PingFangSC-Regular, "Microsoft YaHei", sans-serif;
        font-weight: 100;
        border: 1px solid #e8e8e8;
        border-radius: 30px;
        padding-left: 30px;
        box-sizing: border-box;
        transition: all 0.4s ease;
        box-shadow: 0 0 30px rgba(0, 0, 0, 0.05);

        &::placeholder {
          color: #ddd;
        }

        &:focus {
          border: 1px solid #ff5a05;
          box-shadow: 0 0 30px rgba(0,0,0,.01);
        }
      }

      .btn-submit {
        position: absolute;
        display: block;
        top: 5px;
        right: 5px;
        width: 50px;
        height: 50px;
        font-size: 20px;
        line-height: 56px;
        border-radius: 30px;
        color: #fff;
        background-color: #ff5a05;
        text-align: center;
        transition: all 0.3s ease;

        &:hover {
          background-color: #e85100;
        }

        #icon-search {
          color: #ffffff;
          fill: #ffffff;
          width: 25px;
          height: 25px;
        }
      }
    }
  }

  .tip {
    color:#ff5a05;
  }

  .copyright {
    margin-top: 10px;
    color:gray;
  }
}
</style>
