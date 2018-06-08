<template>
    <header class="main-nav">
        <nav class="nav-class">
          <div class="dash-line"></div>
          <h1 class="logo">Christopher Ellis</h1>

        </nav>
      </header>
</template>

<script>
export default {

}
</script>

<style scoped>

    .logo {
      font-family: 'GTAmerica-Medium', serif;
      font-size: 1em;
      line-height: 1.5625em;
      color: #000000;
      letter-spacing: 0.04em;
      -webkit-font-smoothing: antialiased;
      font-weight: normal;
      padding-top: 3em;
    }

    nav {
      text-align: left;
      display: block;
      padding: 0 20rem;
      /* max-width: 800px; */
      margin: 0 auto;
    }
    
    /*Mobile breakpoint*/
    @media only screen and (max-width: 479px) {

      .main-nav {
        display: block;
        height: 10em;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 0;
      }
    }
</style>
