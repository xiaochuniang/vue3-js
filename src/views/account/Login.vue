<template>
  <div class="login-main">
    <a-form
      name="custom-validation"
      ref="ruleForm"
    >
      <a-form-item>
        <label>用户名</label>
        <a-input type="text" autocomplete="off" />
      </a-form-item>
      <a-form-item>
        <label>密码</label>
        <a-input type="password" autocomplete="off" />
      </a-form-item>

      <a-form-item>
        <a-button type="primary" block>
          Primary
        </a-button>
      </a-form-item>
      
    </a-form>
  </div>
</template>

<script>
import {} from 'vue'
export default {
  
}
</script>

<style lang="scss">
  .login-main{
    width: 100vw;
    height: 100vh;
    background-color: cornflowerblue;
    display: flex;
    align-items: center;
    justify-content: center;
    label{
      color: #FFF;
    }
  }
</style>