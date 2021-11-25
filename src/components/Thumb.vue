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
    width: calc(100% / 6);
    img {
        width: 100%;
        height: 50%;
    }
}




    
</style>