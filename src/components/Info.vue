<template>
<section class="content">
  <div class="container">
      <a class="col">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <span>digital comincs</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <span>digital comincs</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <span>digital comincs</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <span>digital comincs</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <span>digital comincs</span>
      </a>
      
  </div>
</section>
</template>

<script>
export default {
name : 'info',
}
</script>

<style lang="scss" scoped>
$container-width :  950px;
$container-margin :  0 auto;


.content{
    display: flex;
    justify-content: space-around;
    background-color: #0282f9;
    color: white;
    padding-top: 50px;
    padding-bottom: 50px;
    .col{
        width: calc(100%/5);
        display: inline-flex;
        align-items: center;
        img{
            height: 45px;
            width: auto;
        }
        span{
            padding-left: 20px;
        }
    }
}
.container{
    width: $container-width;
    margin: $container-margin;
}

</style>