<template>
   <footer>
      <div class="container">
         <div>
            <a class="sign-up" href="#">SIGN-UP NOW!</a>
         </div>
         <div class="social">
            <h2>FOLLOW US</h2>
            <a href="#">
               <img src="../assets/img/footer-facebook.png" alt="sium" />
            </a>
            <a href="#">
               <img src="../assets/img/footer-periscope.png" alt="sium" />
            </a>
            <a href="#">
               <img src="../assets/img/footer-pinterest.png" alt="sium" />
            </a>
            <a href="#">
               <img src="../assets/img/footer-twitter.png" alt="sium" />
            </a>
            <a href="#">
               <img src="../assets/img/footer-youtube.png" alt="sium" />
            </a>
         </div>
      </div>
   </footer>
</template>

<script>
export default {
   name: "Footer",
   data() {
      return {
         social: [
            { name: "facebook", img: "facebook" },
            { name: "periscope", img: "periscope" },
            { name: "pinterest", img: "pinterest" },
            { name: "twitter", img: "twitter" },
            { name: "youtube", img: "youtube" },
         ],
      };
   },
};
</script>

<style scoped lang="scss">
$container-width :  950px;
$container-margin :  0 auto;
footer {
   background-color: #303030;
   color: #fff;
   padding: 25px;
   .container {
    width: $container-width;
    margin: $container-margin;
    display: flex;
    justify-content: space-between;
    align-items: center;
      .social {
         display: flex;
         justify-content: space-between;
         align-items: center;
         a{
             margin-left: 10px;
         }
      }
   }
   .sign-up {
      text-decoration: none;
      font-size: 18px;
      padding: 5px 10px;
      border: 2px solid #0282f9;
      color: white;
   }
   h2 {
      font-weight: bold;
      color: #0282f9;
      padding-right: 10px;
   }
}
</style>