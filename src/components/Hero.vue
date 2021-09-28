<template>
<div class="container-img">

  <img class="img-formatting" src="../assets/Big_Chungus.png" alt="jumbotron img">

</div>
</template>

<script>
export default {
    name:"Hero"
}
</script>

<style>
.container-img{
    width: 30%;
    margin: auto;
}

.img-formatting{
    object-fit: contain;
    width: 100%;
    height: 100%;
    object-position: center;
}

</style>