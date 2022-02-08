<template>
  <section class="links-section">
      <div class="container">
          <div class="container-links">
          <div class="col">
            <ul>
                <li>DC COMICS</li>
                <li>charaters</li>
                <li>comics</li>
                <li>movies</li>
                <li>TV</li>
                <li>games</li>
                <li>Videos</li>
                <li>news</li>
            </ul>
            <ul>
                <li>shop</li>
                <li>shop dc</li>
                <li>shop dc collectibles</li>
            </ul>
          </div>
          <div class="col">
            <ul>
                <li>DC</li>
                <li>therm of use</li>
                <li>privaci policy(New)</li>
                <li>Ad Choise</li>
                <li>advertising</li>
                <li>jobs</li>
                <li>subscriptions</li>
                <li>talent workshop</li>
                <li>CPSC Cetificates</li>
                <li>ratings</li>
                <li>shop help</li>
                <li>contact us</li>
            </ul>
          </div>
          <div class="col">
            <ul>
                <li>SITES</li>
                <li>DC</li>
                <li>MAD magazine</li>
                <li>DC kids</li>
                <li>DC Universe</li>
                <li>DC Power visa</li>

            </ul>
            </div>
          </div>
          <div class=" col logo-bg">
             
      </div>
      </div>

  </section>
</template>

<script>
export default {
name : 'Links',
}
</script>

<style lang="scss" scoped>
$container-width :  950px;
$container-margin :  0 auto;

.links-section{
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    background-position: center;
    color: white;
}
.container{
  width: $container-width;
  margin: $container-margin;
  display: flex;
  height: 100%;
    img{
        max-width: 100%;
    }
  .col{
    width: calc(32% - 5px);
    display: inline-flex;
    flex-wrap: nowrap;
    justify-content: flex-start;
    flex-direction: column;
      ul{
          padding: 0;
          display: inline;
          li{
              list-style-type: none;
              color: grey;
              text-transform: capitalize;
              font-size: 12px;

          }
          :first-child{
              font-size: 18px;
              font-weight: bold;
              color: white;
          }
      }
  }
.logo-bg{
background-image: url("../assets/img/dc-logo-bg.png");
background-position: center;
background-size: cover;
}
.container-links{
    padding-top: 30px;
    padding-bottom: 30px;
    width: 65%;
}
}
</style>