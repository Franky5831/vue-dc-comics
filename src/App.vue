<template>
  <div id="app">
    <app-header />
    <app-main />
    <app-footer />
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components:{
    AppHeader,
    AppMain,
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
    background-repeat: no-repeat;
    background-size: cover;
    height: 300px;
    padding: 0 10% 0 10%;

  }
  #links{
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    height: 300px;

    ul li:first-child{
      color: white;
      font-size: 30px;
    }
    ul li{
      list-style-type:none;
      color: rgb(131, 131, 131);
      font-size: 15px;
    }
  }
  #socials{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 0 10% 0 10%;

      #followUs{
        display: flex;
        flex-direction: row;
        gap: 35px;
      ul{
      display: flex;
      align-items: center;
      gap: 20px;
      li{
        list-style-type:none;
      }
    }
  }
  }

}
</style>


