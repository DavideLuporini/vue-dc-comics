<template>
<section class="content">
  <div class="container">
      <a class="col">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <span>digital comincs</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
          <span>dc merchandise</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
          <span>subscriptions</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
          <span>comic shop locator</span>
      </a>
      <a class="col">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
          <span>dc power visa</span>
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


    .container{
        width: $container-width;
        margin: $container-margin;
    }
.content{
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #0282f9;
    color: white;
    height: 150px;
    .col{
        width: calc(100%/5);
        display: inline-flex;
        align-items: center;
        padding: 10px;
        img{
            height: 45px;
            width: auto;
            padding-left: 15px;
        }
        span{
            padding-left: 5px;
            text-transform: uppercase;
            font-size: 12px;
        }
    }
        .col:hover{
            border: 1px solid blue;
            background-color: blue;
        }
}

</style>