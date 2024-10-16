<template>
  <div id="app">
  <PageHeader></PageHeader>
    <nav class="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<script>
  import PageHeader from '@/shared/components/PageHeader.vue'
  export default {
    name:'App',
    components:{
      PageHeader
    },
    data(){
      return {
        msg:'Hello World'
      }
    }
  }
</script>

<style>
.nav{
  display: flex;
  justify-content: center;
  gap: 10px;
  align-items: center;
  padding: 10px;
  background-color: #f8f8f8;
}
</style>
