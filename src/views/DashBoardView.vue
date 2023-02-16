<template>
 <div class="container">
   <Aside>

   </Aside>
   <main-content>

   </main-content>
   <aside-crypto-data>
   </aside-crypto-data>

 </div>


</template>

<script>

import Aside from "../components/Aside.vue";
import MainContent from "../components/MainContent.vue";
import AsideCryptoData from "@/components/Aside-Crypto-Data";
export default {
  name: "DashBoardView" ,// name of the component
  components: {
    Aside ,
    MainContent,
    AsideCryptoData ,
 }
}
</script>

<style  lang="scss">
$main-violet : #CC00FFBD;
$main-blue : #1970D6;
$main-yellow : #FAFF00;
$main-black-backgound : #000000;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
background-color: $main-black-backgound;

}
div.container {

  display: grid;
  grid-template-columns: 1fr 3fr 1fr;
  grid-template-rows: 100vh;
  height: 100vh;
  background-color: $main-black-backgound;
}

</style>