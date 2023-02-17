<template>

  <header>
    <nav>

      <div class="logo">
        <img :src="require('@/assets/Minance.png')" alt="image1">
      </div>
      <ul>
        <li class="dashboard"><img :src="require('@/assets/Vector.png')" alt="image1"> DashBoard</li>
        <li><img style="width:38px; height: 38px ;" :src="require('@/assets/Vector-1.png')">Invoices</li>
        <li><img style="width:55px; height: 38px ;" class="Clients" :src="require('@/assets/Vector-2.png')">Clients</li>
        <li><img style="width:44px; height: 43px ;" :src="require('@/assets/Vector-5.png')">Products</li>
        <li><img style="width:40px; height: 33px ;" :src="require('@/assets/Vector-3.png')">Messages</li>
        <li><img style="width:39px; height: 41px ;" :src="require('@/assets/Group.png')">Settings</li>
        <li><img style="width:48px; height: 47px ;" :src="require('@/assets/Vector-4.png')">Help</li>


      </ul>
      <div>
        <li class="LogOut"><img style="width:40px; height: 35px ;" :src="require('@/assets/logOut.png')">Log out</li>
      </div>
    </nav>
  </header>


</template>

<script>
export default {
  name: "Aside-Component"
}
</script>

<style scoped lang="scss">

$main-black-backgound: #000000;
div.logo {


  img {

    margin-top: 48px;
    margin-left: 53px;
    margin-bottom: 70px;
    translate: -25px 0px;


    width: 255px;
    height: 57px;


  }
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
  align-items: center;


  grid-column: 1/2;
  grid-row: 1/2;


  gap: 10px;

  display: flex;
  flex-direction: column;
  align-items: start;
  justify-content: space-between;
  margin-bottom: 50px;


  li   {


    margin-left: 50px;
    width: fit-content;
    height: 50px;


    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 25px;
    line-height: 38px;
    display: flex;


    color: rgba(255, 255, 255, 0.8);

    opacity: 0.8;

    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: start;
    padding: 15px;
    gap: 15px;


    img.Clients {
      width: 55px;
      height: 38px;
      color: #FFFFFF;


    }

    img {
      margin-right: 10px;
      width: 38px;
      height: 38px;
    }



  }

  li.dashboard {

    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 13px 29px;
    margin-bottom: 40px;
    gap: 17px;

    width: 253px;
    height: 65px;
    color: $main-black-backgound;
    font-family: 'Poppins', 'sans-serif';
    font-style: normal;
    font-weight: 400;
    font-size: 25px;
    line-height: 38px;


    border-radius: 17px;

    background: linear-gradient(266.37deg, #FAFF00 -5.82%, #FAFF00 15.95%, #1970D6 41.2%, #6C1182 72.88%);


    img {
      background-color: transparent;
    }

  }
 


}
div{

  li{

     margin-left: 50px;
    width: fit-content;
    height: 50px;


    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 25px;
    line-height: 38px;
    display: flex;


    color: rgba(255, 255, 255, 0.8);

    opacity: 0.8;

    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: start;
    padding: 15px;
    gap: 15px;
  }
  .LogOut {
   
    
  }
}
</style>