<template>
    <div>
        <div class="nav">
            <div class="flex-container">
                <img src="../static/skull.svg" alt="">
                <nav>
                    <ul>
                        <li><a href="">hiccup</a></li>
                        <li><a href="">number</a></li>
                        <li><a href="">color</a></li>
                        <li><a href="">animal</a></li>
                        <li><a href="">food</a></li>
                        <li><a href="">about us</a></li>
                    </ul>
                </nav>
            </div>
          </div>
        <nuxt />
    </div>
</template>

<script>
import index from '../pages/index'
    export default {
        index
    }
</script>

<style >

.nav{
  display: flex;
  flex-direction: row; 
  margin: 0 0  0 0 ; 
}
.flex-container{
    min-width: 100%;
    height: 5.3em;
    border: 1px solid #000;
    display: flex;
    flex-direction: row;
    padding: 0;
    margin: 0;
    justify-content: space-between;
}
img{
  width: 5em;
  /* border: 1px solid #000; */
}
nav{
  display: flex;
  align-items: center;
}
nav ul{
  display: flex;
  justify-content: center;
  
}
nav ul li {
  margin: 0 2em 0 0 ;
  padding: 5px;
  /* border: 1px solid #000; */
  font-size: 1.2em;
  text-transform: uppercase;
  font-weight: 500;

}
</style>>

