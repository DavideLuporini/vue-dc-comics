<template>
<header>
  <div class="container">
    <figure>
      
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
$container-width :  900px;
$container-margin :  0 auto;
  
.container{
  width: $container-width;
  margin: $container-margin;

}
header{
  background-color: white;

  ul{
    display: flex;
    justify-content: flex-end;
    li{
      list-style-type: none;
      margin-left: 20px;
      
    }
  }
}


</style>

