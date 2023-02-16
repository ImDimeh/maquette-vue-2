<template>
<section>

  <div class="head">
    <h1 class="Hi">Hi Rogers</h1>

  <input type="search" placeholder="Search" />

  </div>
</section>

</template>

<script>
export default {
  name: "MainContent"
}
</script>

<style scoped lang="scss">
div {
  
  color: #FAFF00;

  height: 100vh;
  
}
div.head {

  display: flex ;
  flex-direction: row;
  width: 100%;
  height: 80px;

    margin-top: 48px;
    background-color: darkblue;

    justify-content: space-between;
    align-items: end;

  .Hi {

 
  width: 150px;
  
 
  
  color: white;

  height: 60px;
  



font-weight: lighter;


  
}
input {
 
  
  width: 475px;
  
 
  
  color: white;

  height: 60px;
  background-color: white;
  border-radius: 15px;

  display: flex;
flex-direction: row;
align-items: center;
padding: 10px 73px 10px 23px;
gap: 10px;


margin-right: 100px;

}

}



</style>