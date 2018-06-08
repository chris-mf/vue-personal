<template>
  <div id="app">
    <app-header></app-header>
    <app-content></app-content>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppHeader from '@/components/AppHeader'
import AppContent from '@/components/AppContent'
import AppFooter from '@/components/AppFooter'

export default {
  name: 'app',
  components: {
    AppHeader,
    AppContent,
    AppFooter
  },
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">

body {
  margin: 0;
  height: 100%;
  background-color: #F3F0ED;
}

html {
  width: 100%;
}

.highlightText{
  border-bottom: solid rgba(255,255,255,.25);
  border-bottom-width: 1px;
  border-bottom-style: solid;
  border-bottom-color: #D5D5D5
}

.underline {
  position: relative;
  color: #000;
  text-decoration: none;
}

.underline:hover {
  color: #000;
}

.highlightText{
  border-bottom: solid rgba(255,255,255,.25);
  border-bottom-width: 1px;
  border-bottom-style: solid;
  border-bottom-color: #D5D5D5
}

.underline:before {
content: "";
  position: absolute;
  width: 100%;
  height: 2px;
  bottom: -5px;
  left: 0;
  background-color: #000;
  visibility: hidden;
  -webkit-transform: scaleX(0);
  transform: scaleX(0);
  -webkit-transition: all 0.2s ease-in-out 0s;
  transition: all 0.2s ease-in-out 0s;
}

.underline:hover:before {
  visibility: visible;
  -webkit-transform: scaleX(1);
  transform: scaleX(1);
}
  .shiftUp2 {
    display: inline-block;
    -webkit-transform: perspective(0px) translateZ(0);
    -webkit-transition-duration: 0.2s;
    transition-duration: 0.2s;
    -webkit-transition-property: transform;
    transition-property: transform;
    -webkit-transition-timing-function: ease-out;
    transition-timing-function: ease-out;
    text-decoration: none;

  }
  .shiftUp2:hover {
      -webkit-transform: translateY(-5px);
      transform: translateY(-5px);
      color:#D5D5D5;
      text-decoration: none;
  }
  .wrapper {
  // max-width: 800px;
  margin: 0 auto;
  // padding-top: 0%;

  }
.backgroundcolorsquare {
  background-color: #F3F0ED;
  max-height: 525px;
}

</style>
