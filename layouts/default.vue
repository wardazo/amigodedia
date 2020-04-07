<template>
  <div>
    <nav class="navbar is-transparent is-fixed-top ">
      <div class="container is-fluid">
        <div class="navbar-start">
          <img class="absolute" src="~/assets/img/logo-o.png" />
        </div>
        <div class="navbar-end">
          <div class="navbar-item">
            <a class="has-text-white" href="">English</a>
          </div>
          <div class="navbar-item">
            <a class="has-text-white" href="">About</a>
          </div>
          <div class="navbar-item">
            <a class="has-text-white" href="">Get involved</a>
          </div>
          <div class="navbar-item">
            <a class="has-text-white" href="">Join Newsletter</a>
          </div>
          <div class="navbar-item">
            <div class="buttons">
              <a class="button is-primary">
                Pre-register now
              </a>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <nuxt />
    <footer class="footer">
      <div class="has-text-centered has-text-primary is-size-1">
        <a>#amigodeldia</a>
      </div>
      <div class="has-text-centered has-text-primary is-size-5">
        Join the movement
      </div>
      <div class="has-text-centered is-primary p-b-45 p-t-30">
        <span class="p-30 is-inline-block">
          <a class="space">
            <img src="~/assets/img/facebook.png" />
          </a>
        </span>
        <span class="p-30 is-inline-block">
          <a class="space">
            <img src="~/assets/img/twitter.png" />
          </a>
        </span>
        <span class="p-30 is-inline-block">
          <a class="space">
            <img src="~/assets/img/instagram.png" />
          </a>
        </span>
        <span class="p-30 is-inline-block">
          <a class="space">
            <img src="~/assets/img/email.png" />
          </a>
        </span>
      </div>
      <div class="columns">
        <div class="column is-10 is-offset-1 border-top p-l-0 p-r-0">
          <img class="wee middle" src="~/assets/img/logo-o.png" />
          <span class="is-size-7 is-bold p-l-10">
            <b>
              © 2020 Chelsea Consulting & Co. All rights reserved.
              <a>Terms</a> · <a>Privacy</a> · <a>Site Map</a></b
            >
          </span>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
.navbar.is-transparent {
  background: transparent;
}

.navbar.is-transparent {
  font-weight: bold;
  font-size: 16px;
}

.wee {
  width: 50px;
  height: auto;
}
.border-top {
  border-top: 1px solid #114b0b;
  margin-top: 20px;
  padding-top: 20px;
  padding-bottom: 20px;
}
.middle {
  vertical-align: middle;
}
</style>
