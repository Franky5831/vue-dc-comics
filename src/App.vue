<template>
  <div id="app">
    <app-header />
    <main>
      <div id="contentHere">
        <h1>Content goes here</h1>
      </div>
    <app-footer />
    </main>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components:{
    AppHeader,
    AppFooter
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

}




footer{

  #blueBar{
    background-color: #0282F9;
    padding: 50px;
    display: flex;
    justify-content: center;
    gap: 4%;
  }
  a{
    display: flex;
    align-items: center;
    gap: 10px;
    text-decoration: none;

    img{
      width: 60px;
    }

    h1{
      color: white;
      font-weight: 100;
      font-size: 22px;
    }
  }

  #heroFooter{
    height: 500px;
    background-image: url('./assets/img/footer-bg.jpg');
  }
}
</style>


