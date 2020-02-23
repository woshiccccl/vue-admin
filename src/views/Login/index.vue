<template>
  <div id="login">    
  <div class="login-wrap">
     <ul> <li v-for="item in menuTab" :key="item.id" > {{item.txt}} </li> </ul>
  </div>
  </div>
</template>
<script>
export default {
  name: 'login',
  data() {
     return {
        menuTab:[
          {txt:'登录'},
          {txt:'注册'}
        ]
     }
  },
}
</script>
<style lang="scss" scoped>
#login {
  height: 100vh;
  background: #3445af;
}
.login-wrap{
   margin: auto;
   width: 330px
}
</style>
