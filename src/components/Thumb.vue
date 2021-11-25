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
    height: 70%;
    margin: 20px 10px;
    img {
        width: 100%;
    }
}




    
</style>