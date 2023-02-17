<template>
  <div class="Asset-Container">
    <div class="Assets">
      <h4>BITCOIN</h4>
      <h4>121,6450.45</h4>

    </div>
    <div class="Assets2">

    </div>

  </div>

</template>

<script>
export default {
  name: "AssetsComponents" ,
}
</script>

<style scoped lang="scss">

div.Assets {
  position: absolute;


  margin-bottom: 30px;


  background: linear-gradient(98.73deg, #611D8D 35.75%, #2F7EC1 73.26%);
  border-radius: 30px
}

div.Assets2 {
  position: absolute;
  width: 280px;
  height: 174px;
  background: linear-gradient(99.56deg, #FAFF00 35.82%, #29ABE2 64.75%, rgba(255, 255, 255, 0.7) 91.33%);
  border-radius: 30px;

}
div.Asset-Container {
  display: flex;
  flex-direction: column;
}

</style>