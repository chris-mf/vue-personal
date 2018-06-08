<template>
    <div>
        <div id="wrapperID" class="wrapper animated--slide-up">
            <div class="flex-text-wrapper">
                
                    <div class="intro-text-wrapper">
                        <p class="introText">
                            Hello.<br />
                            I’m a digital product designer based in Sydney
                        </p>
                        <p class="introText">I currently call
                            <a href="http://www.mentallyfriendly.com"  target="_blank" class="highlightText shiftUp2">Mentally Friendly
                            </a> my home,
                            occasionally I <a href="https://medium.com/@chris.e" target="_blank" class="highlightText shiftUp2">write words</a> and <a href="https://vsco.co/christophcozy/images/1" target="_blank" class="highlightText shiftUp2">take photos</a>
                        </p>
                    </div>


                <div id="writingsID" class="content">
                    <p class="subheading">
                        Writings
                    </p>
                    <a href="https://medium.com/@chris.e/reducing-interruptions-with-flow-time-820fbbeaf1b8" target="_blank" class="projectlink highlightText shiftUp2">
                        Reducing interruptions with Flow Time</a><br>

                    <a href="https://medium.com/@chris.e/reducing-interruptions-with-flow-time-820fbbeaf1b8" target="_blank" class="projectlink highlightText shiftUp2">
                        Benefits of a war room </a><br>

                    <a href="https://medium.com/@chris.e/reducing-interruptions-with-flow-time-820fbbeaf1b8" target="_blank" class="projectlink highlightText shiftUp2">
                        Why I learnt to code</a>

                    <p class="subheading">
                    Personal projects </p>
                    <a href="http://popcorn.mentallyfriendly.com/" target="_blank" class="projectlink highlightText shiftUp2">
                        Make some popcorn!</a>
                </div>
            
        </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.content {
    background-color: white;
    padding: 5rem 20rem;
}

.intro-text-wrapper {
    padding-bottom: 4rem;
}


.introText {
    font-family: 'GTAmerica-Regular', serif;
    font-size: 2em;
    line-height: 1.5625em;
    color: #333333;
    letter-spacing: 0.04em;
    padding: 0 20rem;
    max-width: 800px;
    margin-top: 2rem;
}

a {
    text-decoration: none;
    /* color: inherit; */
}

.subheading {
  font-family: 'GTAmerica-Medium', serif;
  font-size: 1.5em;
  line-height: 1.5625em;
  color: #333333;
  line-height: 0;
  margin-top: 2.2em;
  margin-bottom: 1.5em;
  letter-spacing: 0.04em;
}

.projectlink {
  font-family: 'GTAmerica-Regular', serif;
  font-size: 1.1em;
  line-height: 1.5625em;
  color: #333333;
  margin-bottom: 1em;
  margin-top: .2em;
  letter-spacing: 0.04em;
  display: inline-block;
}
.animated--slide-up {
    /* opacity: .5; */
    transform: translateY(100px);
    transition: all 1700ms cubic-bezier(0.075, 0.82, 0.165, 1);
}
.animated--slide-up.show {
    transform: translateY(0px);
    opacity: 1;
}


@media only screen and (max-width: 600px) {
   .introText{
    font-size: 1.5em;
    padding: 0 5rem;
    text-align: center;
  }
}

/*Mobile breakpoint*/
@media only screen and (min-width: 601px) and (max-width: 1200px) {
    .introText{
    font-size: 1.5em;
    padding: 0 10rem;
  }


  .introText {
    font-size: 1.5em;
    /* text-align: center; */
  }

.subheading {
  font-size: 1.1em;
  display: flex;
  align-items: center;
  justify-content: center

}

.projectlink {
display: flex;
align-items: center;
justify-content: center
}

}
</style>
