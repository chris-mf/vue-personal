<template>
    <div>
            <div class="wrapper">
        <footer>
          <a>👋<br></a>
          <a href="https://twitter.com/christoph_ellis" target="_blank" class="footer-text">Twitter</a>
          <!-- <a href="https://www.instagram.com/christoph_luke/" target="_blank" class="footer-text shiftUp">Instagram</a> -->
          <a href="https://medium.com/@chris.e" target="_blank" class="footer-text ">Medium</a>
          <a href="https://vsco.co/christophcozy/images/1" target="_blank" class="footer-text ">VSCO</a>
            <a href="https://dribbble.com/chrisellis" target="_blank" class="footer-text">Dribbble</a>
            <!-- <a href="https://github.com/chris-mf" target="_blank" class="footer-text shiftUp">Github</a> -->
      </footer>
  </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
a {
    font-family: 'GTAmerica-Regular', serif;
    font-size: 1em;
    margin-top: 10px;
    color: #000000;
    letter-spacing: 0.04em;
    padding-right: 0px;
    text-decoration: none;
}

    .footer-text{
      font-family: 'GTAmerica-Regular', serif;
      font-size: 1em;
      line-height: 1.5625em;
      color: #000000;
      letter-spacing: 0.04em;
      margin-right: 25px;
      -webkit-font-smoothing: antialiased;
    }

    .footer-text:hover {
      -webkit-transform: translateY(-5px);
      transform: translateY(-5px);
      color:#D5D5D5;
      text-decoration: none;
    }

    footer {
     /* position: absolute; */
     padding-bottom: 3em;
     background-color: white;
     padding: 8rem 20rem 3rem 20rem;

     /*overflow:hidden;*/
    }


    @media only screen and (max-width: 479px) {
    footer {
      /* position: fixed; */
      display: inline;
      float: none;
      flex-flow: column nowrap;
      align-items: flex-start;
      margin-top: 10em;
      margin-bottom: 3em;

    }

}
</style>
