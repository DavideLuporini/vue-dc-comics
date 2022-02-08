<template>
<section class="content">
  <div class="container">
      <div class="col">content goes here</div>
      <div class="col">content goes here</div>
      <div class="col">content goes here</div>
      <div class="col">content goes here</div>
      <div class="col">content goes here</div>
  </div>
</section>
</template>

<script>
export default {
name : 'info',
}
</script>

<style lang="scss" scoped>
$container-width :  900px;
$container-margin :  0 auto;


.content{
    display: flex;
    justify-content: space-around;
    background-color: blue;
    color: white;
    .col{
        width: calc(100%/5);
        display: inline-flex;
    }
}
.container{
    width: $container-width;
    margin: $container-margin;
}

</style>