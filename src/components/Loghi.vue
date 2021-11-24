<template>

    <section>

        <div>
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <div>digital comics</div>
            </div>
                    
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <div>merchandise</div>
            </div>

            <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <div>shop</div>
            </div>

            <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <div>subscriptions</div>
            </div>

            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <div>dc power visa</div>
            </div>
        </div>
        
    </section>
    
</template>

<script>
export default {
  name: 'Loghi',
}

</script>

<style scoped lang="scss">

section {
    background-color: #0282f9;
    height: 120px;
    div {
        display: flex;
        align-items: center;
        color: white;
        width: 80%;
        margin: auto;
        height: 100%;
        text-transform: uppercase;
        font-size: 12px;
        img {
            width: 40px;
            margin-right: 10px ;
        }
    }
}


    
</style>