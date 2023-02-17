<template>
  <div class="TransactionBTC">
    <svg width="39" height="39" viewBox="0 0 41 39" fill="none" xmlns="http://www.w3.org/2000/svg">
      <ellipse cx="20.3283" cy="19.1153" rx="20.3283" ry="19.1153" fill="white"/>
      <path fill-rule="evenodd" clip-rule="evenodd" d="M9.89661 19.1153L20.5957 3.01819V14.7811L9.89661 19.1153ZM30.7598 19.1153L20.5957 14.7868V3.01819L30.7598 19.1153Z" fill="#828384"/>
      <path fill-rule="evenodd" clip-rule="evenodd" d="M20.5957 25.1516L9.89661 19.493L20.5957 15.0909V25.1516ZM30.7598 19.4939L20.5957 25.1516V15.0909L30.7598 19.4939Z" fill="#343535"/>
      <path fill-rule="evenodd" clip-rule="evenodd" d="M9.89661 21.6305L20.5957 27.4381V35.2124L9.89661 21.6305ZM30.7598 21.6305L20.5957 35.2124V27.4374L30.7598 21.6305Z" fill="#828384"/>
      <path fill-rule="evenodd" clip-rule="evenodd" d="M30.7598 19.1153L20.5957 14.7868V3.01819L30.7598 19.1153Z" fill="#2F3030"/>
      <path fill-rule="evenodd" clip-rule="evenodd" d="M30.7598 19.4939L20.5957 15.0909V25.1516L30.7598 19.4939Z" fill="#131313"/>
      <path fill-rule="evenodd" clip-rule="evenodd" d="M30.7598 21.6305L20.5957 27.4374V35.2124L30.7598 21.6305Z" fill="#2F3030"/>
    </svg>

    <div class="Crypto-Name">
      <a>Etherum </a>
      <a>ETC</a>
    </div>
    <div class="Market-Data">
      <a>Market CAP</a>
      <a class="Market-Data-Value">$40,243.70</a>
    </div>
    <div class="Change">
      <a>24h change</a>
      <a class="ValueChange"> -1,56</a>
    </div>
    <div class="svg-container">
      <svg width="151" height="18" viewBox="0 0 151 18" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M4 7.04242C6.73136 9.3383 14.7845 12.5525 25.146 7.04242C35.5076 1.53231 42.151 4.74654 44.1774 7.04242C46.4683 10.3223 52.8473 15.898 60.037 11.9622C69.024 7.04242 74.3105 2.12267 86.4695 7.04242C98.6285 11.9622 108.408 16.8819 112.902 11.9622C117.396 7.04242 142.506 2.12267 147 7.04242" stroke="url(#paint0_linear_16_134)" stroke-width="7" stroke-linecap="round"/>
        <defs>
          <linearGradient id="paint0_linear_16_134" x1="75.5" y1="14" x2="75.5" y2="4" gradientUnits="userSpaceOnUse">
            <stop stop-color="#091BA9"/>
            <stop offset="1" stop-color="#4D91A5"/>
          </linearGradient>
        </defs>
      </svg>


    </div>
    <div class="TradeButton-Container">
      <button>TRADE</button>
    </div>


  </div>
</template>

<script>
export default {
  name: "TransactionETH",
}

</script>

<style scoped lang="scss">
div.TransactionBTC {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;

  align-items: center;
  width: 100%;
  height: 80px;
  margin: 10px 50px;
  text-align: center;
  justify-content: space-around;

  background: rgba(32, 35, 43 , 0.7);





  border-radius: 30px;


  .svg-container{
    background-color: transparent;



  }
  svg {
    margin: 10px 10px 15px 10px;




  }
}
div.TransactionBTC:nth-child(1){
  background-color: red;
  color: green;
}
div.Crypto-Name {
    background: rgba(32, 35, 43 );
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  width: 20%;
  height: 80px;
  text-align: center;


  a {

    width: 55px;
    height: 21px;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 17px;
    line-height: 21px;
    /* identical to box height */

    display: flex;
    align-items: center;
    background-color: transparent;

    color: #FFFFFF;
  }

}
div.Market-Data{
   background: rgba(32, 35, 43 );


  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  width: 20%;
  height: 80px;
  text-align: center;
  a {
    width: 100px;
    height: 21px;
    background-color: transparent;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 17px;
    line-height: 21px;
    /* identical to box height */

    display: flex;
    align-items: center;

    color: #FFFFFF;

    ;
  }
  a.Market-Data-Value{
 background: rgba(32, 35, 43 );
    width: 97px;
    height: 21px;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    /* identical to box height */

    display: flex;
    align-items: center;

    color :  rgba(108, 17, 130, 1);






  }

}
div.Change{
   background: rgba(32, 35, 43 );

  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  width: 20%;
  height: 80px;
  text-align: center;
  a {

    width: 100px;
    height: 21px;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 17px;
    line-height: 21px;
    /* identical to box height */

    display: flex;
    align-items: center;

    color: #FFFFFF;
    background-color: transparent;


  }
  a.ValueChange{

    width: 46px;
    height: 21px;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 17px;
    line-height: 21px;
    /* identical to box height */

    display: flex;
    align-items: center;

    color: red;


  }

}
div.TradeButton-Container {
   background: rgba(32, 35, 43 );

  width: 20%;
  height: 80px;

  border-top-right-radius: 30px;
   border-bottom-right-radius: 30px;




  button {

    color: white;

    padding: 10px 20px;

    border-radius: 30px;
    translate: 0px 15px;

  }
}
</style>