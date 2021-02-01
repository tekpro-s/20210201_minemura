<template>
  <footer class="top-footer">
    <div class="footer-bar">
      <div class="flex">
        <h1 class="fotter-logo">estra inc.</h1>
        <nav class="fotter-nav">
          <ul>
            <li><a href="#">home</a></li>
            <li><a href="#">about</a></li>
            <li><a href="#">service</a></li>
            <li><a href="#">works</a></li>
            <li><a href="#">price</a></li>
            <li><a href="#">contact</a></li>
          </ul>
        </nav>
      </div>
    </div>
    <small>Copyright 2019 estra inc. All Rights Reserved.</small>
  </footer>
</template>

<style scoped>
.footer-bar {
  height: 70px;
  line-height: 70px;
}

.top-footer {
  background: #000;
  text-align: center;
}

.top-footer small {
  text-align: center;
  color: #fff;
}

.fotter-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #fff;
  line-height: 70px;
}

.fotter-nav li {
  display: inline-block;
  margin-right: 35px;
  font-size: 16px;
}

.fotter-nav a {
  color: #fff;
}

/*------------------------*/
/*    レスポンシブデザイン   */
/*------------------------*/
@media screen and (max-width: 768px) {
  .fotter-logo {
    margin-left: 0px;
    margin: 0 auto;
  }
  .fotter-nav {
    display: none;
  }
}
</style>