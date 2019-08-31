<template>
  <div>
    <section class="sec0">
      <div class="box">
        <h2>
          <span>S</span>
          <span>U</span>
          <span>P</span>
          <span>E</span>
          <span>R</span>
          <span>S</span>
          <span>I</span>
          <span>T</span>
          <span>I</span>
          <span>O</span>
          <span>N</span>
        </h2>
      </div>
    </section>
    <section class="sec1">
      <div class="content1">

      </div>
      <div class="content2">
        
      </div>
    </section>
    <section class="sec2">

    </section>
    <section class="sec3">

    </section>
    <section class="sec4">

    </section>
    <section class="sec5">

    </section>
  </div>
</template>

<script>

export default {
  components: {

  }
}
</script>

<style>

section{
  border: 1px solid #000;
  background: rgb(255, 255, 255);
  height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.box{
  margin: 10px 0 0 0 ;
  background: rgb(10, 9, 9);
  width: 50vh;
  height: 50vh;
  border: 2px solid rgb(255, 255, 255) ; 
}
.sec0, .sec2, .sec4 {
    background: rgb(20, 18, 18);
}
.content1{
  border: 1px solid #000;
  width: 50vh;
  height: 50vh;
}
.content2{
  border: 1px solid #000;
  width: 50vh;
  height: 50vh;
  margin: 0 0 0 2em;
}
.box{
    display: flex;
  justify-content: center;
  align-items: center;
}
h2 {

  color: rgb(255, 255, 255);
  font-size: 5em;
  font-weight: 900;
  text-transform: uppercase;
  display: flex;
  text-align: center;

}
h2 span {
  transition: 3.5s;
}
h2:hover span {
  filter: blur(20px);
  opacity: 0;
  transform: scale(2)
}

h2 span:ntn-child(10n+1){
  transition-delay: 0.1s;
}
h2 span:ntn-child(10n+2){
  transition-delay: 0.2s;
}
h2 span:ntn-child(10n+3){
  transition-delay: 0.3s;
}
h2 span:ntn-child(10n+4){
  transition-delay: 0.4s;
}
h2 span:ntn-child(10n+5){
  transition-delay: 0.5s;
}
h2 span:ntn-child(10n+6){
  transition-delay: 0.6s;
}
h2 span:ntn-child(10n+7){
  transition-delay: 0.7;
}
h2 span:ntn-child(10n+8){
  transition-delay: 0.8s;
}
h2 span:ntn-child(10n+9){
  transition-delay: 0.9s;
}
h2 span:ntn-child(10n+10){
  transition-delay: 1s;
}
/* 
@media only screen  and (min-width: 300px){
      
    h2 {

      color: rgb(255, 255, 255);
      font-size: 1em;
      font-weight: 900;
      text-transform: uppercase;
      display: flex;
      text-align: center;

    }
    h2 span {
      transition: 2.5s;
    }
    h2:hover span {
      filter: blur(20px);
      opacity: 0;
      transform: scale(2)
    }

    h2 span:ntn-child(10n+1){
      transition-delay: 0.1s;
    }
    h2 span:ntn-child(10n+2){
      transition-delay: 0.2s;
    }
    h2 span:ntn-child(10n+3){
      transition-delay: 0.3s;
    }
    h2 span:ntn-child(10n+4){
      transition-delay: 0.4s;
    }
    h2 span:ntn-child(10n+5){
      transition-delay: 0.5s;
    }
    h2 span:ntn-child(10n+6){
      transition-delay: 0.6s;
    }
    h2 span:ntn-child(10n+7){
      transition-delay: 0.7;
    }
    h2 span:ntn-child(10n+8){
      transition-delay: 0.8s;
    }
    h2 span:ntn-child(10n+9){
      transition-delay: 0.9s;
    }
    h2 span:ntn-child(10n+10){
      transition-delay: 1s;
    }
} */
</style>
