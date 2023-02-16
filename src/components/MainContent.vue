<template>
<section>

  <div class="head">

    
    <h1 class="Hi">Hi Rogers</h1>
    <div>
            <svg width="35" height="34" viewBox="0 0 35 34" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M29.9566 26.3967C30.6547 25.2949 31.0673 24.02 31.0673 22.6349C31.0673 18.7157 27.8781 15.5519 23.9272 15.5519C19.9764 15.5519 16.7871 18.7157 16.7871 22.6349C16.7871 26.5541 19.9764 29.7178 23.9113 29.7178C25.3076 29.7178 26.6087 29.3086 27.7035 28.6161L32.654 33.5269L34.9071 31.2918L29.9566 26.3967ZM23.9272 26.5699C21.7376 26.5699 19.9605 24.807 19.9605 22.6349C19.9605 20.4628 21.7376 18.6999 23.9272 18.6999C26.1168 18.6999 27.8939 20.4628 27.8939 22.6349C27.8939 24.807 26.1168 26.5699 23.9272 26.5699ZM23.356 13.1909C22.1819 13.2224 21.0553 13.4743 20.024 13.8992L19.1513 12.5928L13.1219 22.3201L8.34596 16.7796L2.5863 25.9245L0 24.083L7.93342 11.491L12.6935 17L19.0402 6.76906L23.356 13.1909ZM27.4655 13.9779C26.45 13.5372 25.3552 13.2696 24.2128 13.2067L32.3366 0.473091L34.9071 2.3304L27.4655 13.9779Z" fill="black"/>
        </svg>
            
      <input type="search" placeholder="Search" />
    </div>

   

  </div>
   
    <div class="money-data">
      <a>Total Balance </a>
      <a>0.97894652 </a>
      <a>$40,123.56</a>
    </div>
    <ul>
      <li>Portfolio</li>
      <li>Funding </li>
      <li>Assets </li>
      <li> P2P</li>
    </ul>
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
    

    justify-content: space-between;
    align-items: end;

  .Hi {

 
  width: 150px;
  
 
  
  color: white;

  height: 60px;
  



font-weight: lighter;


  
}
div{
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 10px;

    height: 60px;
    width: 675px;

    padding-left: 15px;
    background-color: white;
    border-radius: 15px;
    margin-right: 100px;
    translate: 0px -25px;
    
    svg {
      
      fill: white;
      background-color: white;
    }


input {
 
 
  
  width: 475px;
  border: none;
 
  
  color: white;

  height: 60px;
  background-color: white;
  border-radius: 15px;

  display: flex;
flex-direction: row;
align-items: center;
padding: 10px 73px 10px 23px;
gap: 10px;




}}

}

div.money-data {
  
  color: white;
  width: 200px;
  height: 100px;
  display: flex;
  margin-top: 50px;
  

  display: flex;
  flex-direction: column;
  align-items: start;
  justify-content: center;
  gap: 10px;
  :nth-child(1){
  font-style: normal;
font-weight: 900;
font-size: 22px;
line-height: 33px;

color: #FFFFFF;

opacity: 0.8;



  }

   :nth-child(2){
 font-style: normal;
font-weight: 700;
font-size: 29px;
line-height: 44px;

color: #FFFFFF;

    


  }
  :nth-child(2):after{
          content: "BTC";
      position: absolute;
        width: 50px;
      height: 25px;
      left: 590px;
        top: 208px;

      font-size: 20px;
      
      background-color: yellow;
     

      
      color: black;
     
      border-radius: 8px;

      font-style: normal;
font-weight: 700;
font-size: 15px;
line-height: 31px;
translate: -5px 0px;
      


  }
  
   :nth-child(3){
    font-style: normal;
font-weight: 600;
font-size: 22px;
line-height: 33px;

color: #FFFFFF;

opacity: 0.7;
   }

  a {
    font-family: 'Poppins';
font-style: normal;
font-weight: 900;
font-size: 22px;
line-height: 33px;

color: #FFFFFF;


  }
}


</style>