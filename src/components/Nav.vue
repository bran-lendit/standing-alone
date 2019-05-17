<template>
  <div id="navigation-container">
    <div class="navigation-wrapper">
      <router-link to="/">홀로서기</router-link>
      <div class="navigation-menu">
        <ul>
          <li>
            <router-link to="/">홈</router-link>
          </li>
          <li>
            <router-link to="/store">스토어</router-link>
          </li>
          <li>
            <router-link to="/">커뮤니티</router-link>
          </li>
        </ul>
      </div>
      <div class="navigation-user-side">
          <button>글쓰기</button>
          <router-link to="">로그인</router-link>
          <router-link to="">회원가입</router-link>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'nav',
}
</script>
<style lang="scss">
  #navigation-container {
    height: 55px;
    padding: 25px 40px;
    display: flex;
    .navigation-wrapper {
      display: flex;
      align-items: center;
      width: 100%;
      justify-content: space-between;
      > a {
        text-decoration: none;
        color: black;
      }

      .navigation-menu {
        > ul {
          display: flex;
          > li {
            list-style-type: none;
            a {
              text-decoration: none;
              font-size: 18px;
              color: black;
              padding-right: 16px;
            }
            a:hover {
              color: #35C5F0;
            }
          }
        }
      }
      .navigation-user-side {
        display: flex;
        align-items: center;
        margin-left: auto;
        button {
          width: 74px;
          height: 32px;
          border: 1px solid #35C5F0;
          border-radius: 16px;
          font-size: 15px;
          color: #09ADDB;
          font-weight: bold;
          text-align: center;
          transition: .1s background, .1s color;
          margin-right: 8px;
        }
        a {
            text-decoration: none;
            font-size: 18px;
            color: black;
        }
        a:nth-child(3):before {
          content: '';
          display: inline-block;
          width: 0;
          height: 15px;
          padding-left: 10px;
          margin-right: 10px;
          vertical-align: -2px;
          border-right: 1px solid #757575;
        }
      }
    }
  }
</style>
