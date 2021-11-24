<template>
  <header>
          <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li v-for="link, i in links" :key="i" :class="link.here === true ? 'active' : ''">{{link.text}}</li>
        </ul>
  </header>
</template>

<script>
export default {
  name: 'Myheader',
 data(){
     return {
         links: [
             {
                 text: "Characters",
                 url: "*",
                 Here: false
             },
             {
                 text: "Comics",
                 url: "*",
                 Here: true
             },
             {
                 text: "Movies",
                 url: "*",
                 Here: false
             },
             {
                 text: "TV",
                 url: "*",
                 Here: false
             },
             {
                 text: "Games",
                 url: "*",
                 Here: false
             },
             {
                 text: "Collectibles",
                 url: "*",
                 Here: false
             },
             {
                 text: "Videos",
                 url: "*",
                 Here: false
             },
             {
                 text: "Fans",
                 url: "*",
                 Here: false
             },
             {
                 text: "News",
                 url: "*",
                 Here: false
             },
             {
                 text: "Shop",
                 url: "*",
                 visuability: false
             }
         ]
     }
 }
  
}
</script>

<style scoped lang="scss">
header {
    height: 100px;
    display: flex;
    justify-content: space-between;
    width: 80%;
    margin: 30px auto;
    img {
    width: 100px;
        }
        ul {
            display: flex;
            align-items: center;
            li {
                display: inline-block;
                margin: 0 10px;
                font-size: 12px;
                font-weight: bold;
                &:hover {
                    color:#0c7cec;
                    cursor: pointer;
                }
                &.active{
                    color:#0c7cec;
                    padding-bottom: 50px;
                    border-bottom: 5px solid;
                }
            }
        }
    }
    
</style>