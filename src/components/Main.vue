<template>
    <div class="container_main">
        <div>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMIC</span>
        </div>
        <div>
             <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <span>DC MERCHANDISE</span>
        </div>
        <div>
             <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>COMIC SHOP LOCATOR</span>
        </div>
        <div>
             <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <span>SUBSCRIPTIONS</span>
        </div>
        <div>
             <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span>DC POWER VISA</span>
        </div>
    </div>
</template>

<script>
export default {
    name: "Main"
}
</script>

<style scoped>
    .container_main {
        height: 140px;
        background-color: #0282f9;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    span {
        font-size: 12px;
        color: white;
        vertical-align: top;
        line-height: 75px;
        cursor: pointer;
    }

    img {
        height: 32px;
        margin: 20px;
        cursor: pointer;
    }
    
</style>