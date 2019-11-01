<template>
<div class="welcome">
  <h1>{{ msg }}</h1>
  <router-link to="/">ホーム</router-link>
  <router-link to="/profile">プロフィール</router-link>
  <router-link to="/works">制作物</router-link>
</div>
</template>

<script>
export default {
  name: 'welcome',
  data () {
    return {
      msg: '制作物'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

a {
  color: #42b983;
}
</style>
