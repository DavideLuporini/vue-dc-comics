<template>
<section class="content">
  <div class="container">
      <div id="title">

        ----------> content goes here >------------
      </div>
  </div>
</section>
</template>

<script>
export default {
name : 'Content',
}
</script>

<style lang="scss" scoped>
$container-width :  950px;
$container-margin :  0 auto;
.content{
    background-color: black;
    color: white;
}
.container{
    width: $container-width;
    margin: $container-margin;
    #title{
        font-size: 29px;
        padding-top: 45px;
        padding-bottom: 45px;
    }
}

</style>