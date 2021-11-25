<template>

    <div class="comics">
        <img :src="details.thumb" alt="">
        <h4>{{details.series}}</h4>
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
    height: 200px;
    margin: 10px 10px;
    img {
        width: 100%;
        height: 80%;
        object-fit: none;
        object-position: top;
    }
    h4 {
        margin-top: 10px ;
    }
}





    
</style>