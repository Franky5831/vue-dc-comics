<template>
  <div id="app">

    <main>
      <app-header />
      <div id="contentHere">
        <h1>Content goes here</h1>
      </div>
      <div id="blueBar">
        
      </div>
    </main>
  </div>
</template>

<script>
import AppHeader from '.components/AppHeader.vue'

export default{
  name: 'App',
  components:{
    AppHeader,
  },
  data(){

  },
  methods:{

  }
}

</script>
<style lang="scss">

</style>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  background-color: black;
}
#app{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  background-color: #313131;
}
header{
  display: flex;
  justify-content: space-around;
  background-color: white;

  img{
    padding: 20px;
  }
  #optionsHeader{
    display: flex;
    justify-content: space-evenly;
    gap: 20px;
    align-items: center;

    a{
      color: #2c3e50;
      text-decoration: none;
    h1{
      font-size: 20px;
    }
    }

  }
}

main{
  #contentHere{
    background-color: #1C1C1C;
    padding: 100px;
    color: white;
    text-align: center;
  }

  #blueBar{
    background-color: #0282F9;
    height: 200px;
    display: flex;
  }
}
</style>


