<template>
    <div class="container">
        <div class="contain">
            <div class="card"></div>
            <div class="menu">
                <ul>
                    <li>
                        <img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS
                        </span>
                    </li> 
                    <li>
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <span>DC MERCHANDISE</span>
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <span>SUBSCRIPTION</span>
                    </li>
                    <li>
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <span>COMICS SHOP LOCATOR</span>
                    </li>
                    <li>
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <span>DC POWER VISA</span>
                    </li>  
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Main',
    data() {

    }
}
</script>

<style lang="scss" scoped>
    .card {
        width: 100%;
        height: 100px;
        background-color: black;
    }

    .menu {
        height: 100%;
        height: 150px;
        background-color: #0282f9;
        display: flex;
        align-items: center;
        
    }

    ul {
        display: flex;
        list-style: none;
        width: 70%;
        margin: 0 auto;
        justify-content: space-between;
        
    }

    li {
        display: flex;
        align-items: center;
        color: white;
    }

    span {
        font-size: 0.9em;
        padding-left: 0.5em;
    }

    img {
        padding-left: 1em;
        width: 50px;
    }
</style>