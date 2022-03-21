<template>

<h1>Buy my NFT's</h1>
<div class="container">
       <div class="nft-box">
        <img src="https://img.rarible.com/prod/image/upload/t_image_big/prod-itemImages/0xb66a603f4cfe17e3d27b87a8bfcad319856518b8:85838424642186781925262541420103558419881689205735539342218558377551506440218/2498004e" alt="doom-creeper">
       <div class="box-info">
            <h1>Doom Creeper</h1>
            <div class="box-price">
                <h3>1/1</h3>
                <h3>0.5 ETH</h3>
            </div>
       </div>
   </div>

      <div class="nft-box">
        <img src="https://img.rarible.com/prod/image/upload/t_image_big/prod-itemImages/0xb66a603f4cfe17e3d27b87a8bfcad319856518b8:85838424642186781925262541420103558419881689205735539342218558377551506440210/594c281" alt="bleach-creeper">
       <div class="box-info">
            <h1>Hollow Creeper</h1>
            <div class="box-price">
                <h3>1/1</h3>
                <h3>0.5 ETH</h3>
            </div>
       </div>      
   </div>

         <div class="nft-box">
        <img src="https://img.rarible.com/prod/image/upload/t_image_big/prod-itemImages/0xb66a603f4cfe17e3d27b87a8bfcad319856518b8:85838424642186781925262541420103558419881689205735539342218558377551506440215/a8f58a0f" alt="bleach-creeper">
       <div class="box-info">
            <h1>9 Tails Creeper</h1>
            <div class="box-price">
                <h3>1/1</h3>
                <h3>0.5 ETH</h3>
            </div>
       </div>      
   </div>

            <div class="nft-box">
        <img src="https://img.rarible.com/prod/image/upload/t_image_big/prod-itemImages/0xb66a603f4cfe17e3d27b87a8bfcad319856518b8:85838424642186781925262541420103558419881689205735539342218558377551506440205/947fdfa4" alt="bleach-creeper">
       <div class="box-info">
            <h1>Reptile Creeper</h1>
            <div class="box-price">
                <h3>1/1</h3>
                <h3>0.5 ETH</h3>
            </div>
       </div>      
   </div>

</div>
</template>

<script>

</script>

<style scoped>
.container{
    display: flex;
    justify-content: center;
    align-items: center;
}
.nft-box{
    display: flex;
    flex-direction: column;
    width:250px;
    border: 1px solid darkcyan;
    border-radius: 10px;
    margin: 1%;
    
}
.box-info{
    padding-left: 10px;
    padding-right: 10px;
    padding-bottom: 10px;
}
.box-price{
    display: flex;
    width: 100%;
    justify-content: space-between;
}
.nft-box h1{
    color: darkcyan;
}

h1{
    text-align: center;
}
</style>