<template>
  <div class="login-form">
    <div class="g-form">
      <div class="g-form-line">
        <span class="g-form-label">用户名：</span>
        <div class="g-form-input">
          <input type="text" placeholder="请输入用户名">
        </div>
        </div>
      <div class="g-form-line">
        <span class="g-form-label">密码：</span>
         <div class="g-form-input">
          <input type="password" placeholder="请输入密码">
        </div>
      </div>
      <div class="g-form-line">
        <span class="g-form-label">确认密码：</span>
        <div class="g-form-input">
          <input type="password" placeholder="请输入密码">
        </div>
      </div>
      <div class="g-form-btn">
    <a class="button" @click="onLogin">注册</a>
    </div>
    </div>
  </div>
</template>

<script>
export default { }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
