<template>
  <div class="page login-page">
    <div class="container d-flex align-items-center">
      <div class="form-holder has-shdow">
        <div class="row">
          <!-- log area-->
          <div class="col-lg-6">
            <div class="info d-flex align-items-center">
              <div class="logo">
                <h1>欢迎登录</h1>
                <p>中国xxxxxxxxxx集团安徽有限公司</p>
              </div>
            </div>
          </div>
          <!-- form area -->
          <div class="col-lg-6 bg-white">
            <div class="form d-flex align-items-center">
              <div class="content">
                <form action="" method="post" class="form-validate" id="login-form">
                  <div class="form-group">
                    <b-input id="username" name="username" required="true" data-msg="请输入用户名" class="input-material" placeholder="请输入用户名"></b-input>
                  </div>
                  <div class="form-group">
                    <b-input type="password" name="password" required="true" data-msg="请输入密码" class="input-material" placeholder="请输入密码"></b-input>
                  </div>
                  <b-button class="btn btn-primary" id="btnLogin">登录</b-button>
                  <div style="margin-top:-20px;">
                    <div class="custom-control custom-checkbox" style="float:right;">
                      <b-form-checkbox id="chkremenber">记住密码</b-form-checkbox>
                    </div>
                  </div>
                </form>
                <p style="clear:both;">
                  <small>忘记密码？<b-link href="#">立即找回</b-link></small>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import '../assets/css/login.css'
export default {
    name: 'Login'
}
</script>