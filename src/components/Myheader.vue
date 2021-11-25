<template>
  <header>
          <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li v-for="link, i in links" :key="i" :class="link.Here === true ? 'active' : ''">{{link.text}}</li>
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
                 Here: false
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
    align-items: center;
    width: 80%;
    margin: auto;
    img {
    width: 60px;
    height: 60px;
        }
        ul {
            display: flex;
            align-items: center;
            li {
                display: inline-block;
                margin: 0 10px;
                font-size: 12px;
                font-weight: bold;
                padding: 40px 0;
                &:hover {
                    color:#0c7cec;
                    cursor: pointer;
                }
                &.active{
                    color:#0c7cec;
                    
                    border-bottom: 5px solid;
                }
            }
        }
    }
    *{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>