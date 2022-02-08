<template>
<header>
  <div class="container">
    <figure>
      <img src="../assets/img/dc-logo.png" alt="">
    </figure>
    <ul>
      <li>characters</li>
      <li>comics</li>
      <li>movies</li>
      <li>tv</li>
      <li>games</li>
      <li>collectibles</li>
      <li>videos</li>
      <li>fans</li>
      <li>news</li>
      <li>shop</li>
    </ul>
  </div>
</header>
</template>

<script>
export default {
  name: 'Header',
  
}
</script>


<style scoped lang="scss">
$container-width :  950px;
$container-margin :  0 auto;
  
.container{
  width: $container-width;
  margin: $container-margin;
  display: flex;
    justify-content: space-between;

}
header{
  background-color: white;
  padding-bottom: 10px;
  padding-top: 10px;
  img{
    width: 70px;
    height: 100%;
    
  }

  ul{
    display: flex;
    justify-content: flex-end;
    margin-bottom: 0px;
    align-items: center;
    align-content: center;
     li:hover {
        border-bottom: 5px solid blue ;
      }
    li{
      list-style-type: none;
      padding-left: 10px;
      padding-right: 10px;
      text-transform: uppercase;
      font-weight: bold;
      font-size: 10px;
      align-items: center;
      display: flex;
      height: 100%;
    }
  }
}


</style>

