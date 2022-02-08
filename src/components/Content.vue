<template>
<section class="content">
  <div class="container">
content goes here 
  </div>
</section>
</template>

<script>
export default {
name : 'Content',
}
</script>

<style lang="scss" scoped>
$container-width :  900px;
$container-margin :  0 auto;
.content{
    background-color: black;
    color: white;
}
.container{
    width: $container-width;
    margin: $container-margin;
}

</style>