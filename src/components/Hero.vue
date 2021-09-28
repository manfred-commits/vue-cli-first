<template>
<div class="container-img">

  <img class="img-formatting" src="https://cdn.vox-cdn.com/thumbor/rw5wQeIgykyM4wlKhSNKTs6N-io=/0x0:1250x694/1200x800/filters:focal(525x247:725x447)/cdn.vox-cdn.com/uploads/chorus_image/image/69049871/Big_Chungus.0.png" alt="jumbotron img">

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