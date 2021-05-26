<template>
  <header>
    <nav class="container">
      <a href="/">
        <img src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/wdev.svg"
         alt="logo WDEV" 
         id="logo"
        >
      </a>

      <img src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg"
       alt="Abrir menu" 
       id="menu-btn"
      >
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
  header{
    background-color: var(--color-background-nav);
    height: 60px;
    width: 100%;
  }
  nav{
    display: flex;
  }
  #logo{
    width: 130px;
  }
  #menu-btn{
    width: 30px;
  }
</style>