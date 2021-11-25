<template>

    <footer>

        <div class="container">
            <div class="nav">
                <h4>DC Comics</h4>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>

                <h4>Shop</h4>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <div class="nav">
                <h4>DC</h4>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>

            <div class="nav">
                <h4>Sites</h4>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>

            <div class="logo">

                <img src="../assets/img/dc-logo-bg.png" alt="">

            </div>
        </div>

    </footer>
    

</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped lang="scss">
footer {
    height: 300px;
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    .container {
        display: flex;
        width: 80%;
        margin: auto;
        .nav {
            width: 10%;
            margin: 30px 0 ;
        }
        .logo {
            width: 70%;
            text-align: end;
        }
        img {
            height: 300px;
            width: 600px;
            object-fit: none;
        }
        h4 {
            color:white;
            margin: 10px 0;
        }
        li  {
            list-style-type: none;
            font-size: 10px;
            color: #808A89;
            margin-top: 5px;
        }
    }
}


</style>