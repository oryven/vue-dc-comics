<template>

    <div class="comics">
        <img :src="details.thumb" alt="">
        <h4>{{details.series}}</h4>
        <div>{{details.type}}</div>
        <div>{{details.price}}</div>
    </div>

</template>

<script>
export default {
  name: 'Thumb',
  props: {
      details: Object
  }
}

</script>

<style scoped lang="scss">

.comics {
    width: calc(100% / 6 - 20px);
    height: 250px;
    margin: 10px 10px;
    img {
        width: 100%;
        height: 170px;
        object-fit: none;
        object-position: top;
    }
    h4 {
        margin-top: 10px ;
    }
}
 
</style>