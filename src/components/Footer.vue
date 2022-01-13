<template>
    <div class="container">
        <div class="info">
            
        </div>
        <div class="footer-social">
            <div class="social">
                <span class="sign-up">SIGN-UP NOW!</span>
                <div class="footer-follow">
                    <span class="follows">FOLLOW US</span>
                    <ul>
                        <li>
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </li> 
                        <li>
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </li>
                        <li>
                            <img src="../assets/img/footer-pinterest.png" alt="">  
                        </li>
                        <li>
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </li>  
                    </ul> 
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer',
    data() {

    }
}
</script>

<style lang="scss" scoped>
    .container {
        width: 100%;
        height: 500px;
    }

    .info {
        width: 100%;
        height: 80%;
        background: url(../assets/img/footer-bg.jpg);
    }

    .footer-social {
        height: 20%;
        display: flex;
        align-items: center;
        background-color: #303030;
    }

    .social {
        width: 70%;
        margin: 0 auto;
        display: flex;
        justify-content: center;
        align-items: center;
        justify-content: space-between;
    }

    .follows {
        color: #0282f9;
        font-size: 1.3em;
        font-weight: bold;
    }

    .footer-follow {
        display: flex;
        align-items: center;
    }

    .sign-up {
        color: white;
        border: 2px solid #0282f9;
        padding: 0.7em;
    }

    ul {
        display: flex;
        list-style: none;
    }

    li {
        padding-left: 1em;
    }
</style>