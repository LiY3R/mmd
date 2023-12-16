<script setup>
</script>

<template>
    <header>
      <div class="navbar"> 
        <div class="logodiv">
          <img src="../assets/apple.png" alt="apple" class="logo">
        </div>
        <div class="welcome">
          Phone library
        </div>
        <div class="write">
          <input type="text" class="inp" placeholder="جستجو">
        </div>
      </div>
      <div class="menu">
        <div class="mitems">
          <RouterLink to="/about">درباره</RouterLink>
        </div>
        <div class="mitems">
          <RouterLink to="/"> خانه </RouterLink>
        </div>
      </div>
    </header>

</template>
<style scoped>
  header{
    width: 100%;
    height: 150px;
    background-color: rgb(206, 206, 206);
    direction: rtl;
  }
  .navbar {
    width: 100%;
    height: 100px;
    display: flex;
  }
  .logodiv {
    width: 300px;
    height: 100%;
  }
  .logo {
    width: 180px;
    margin-right: 50px;
  }
  .welcome {
    width: 710px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 30px;
  }
  .write {
    width: 300px;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .inp {
    border: solid 1px gray;
    border-radius: 15px;
    width: 200px;
    height: 30px;
    font-size: 16px;
    box-shadow: 0rem 0px 20px 1px;
  }

  .menu {
    width: 100%;
    height: 50px;
    background-color: black;
    display: flex;
    direction: ltr;

  }
  .mitems {
    width: 50px;
    height: 100%;
    color: white;
    font-size: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: yellow;
  }

</style>
  
