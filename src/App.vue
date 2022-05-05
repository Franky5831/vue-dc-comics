<template>
  <div id="app">
    <header>
      <img src="./img/dc-logo.png" alt="">
      <div id="optionsHeader">
        <a href="#">
          <h1>characters</h1>
        </a>
        <a href="#">
          <h1>comics</h1>
        </a>
        <a href="#">
          <h1>movies</h1>
        </a>
        <a href="#">
          <h1>tv</h1>
        </a>
        <a href="#">
          <h1>games</h1>
        </a>
        <a href="#">
          <h1>collelctibles</h1>
        </a>
        <a href="#">
          <h1>videos</h1>
        </a>
        <a href="#">
          <h1>fans</h1>
        </a>
        <a href="#">
          <h1>news</h1>
        </a>
        <a href="#">
          <h1>shop</h1>
        </a>
      </div>
    </header>
    <main>
      <div id="contentHere">
        <h1>Content goes here</h1>
      </div>
      <div id="blueBar">
        
      </div>
    </main>
  </div>
</template>

<script>

</script>

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
  }
}
</style>


