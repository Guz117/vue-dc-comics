<template>
    <div class="container">
        <div class="footer">
            <div class="info">
                <div class="social-info">
                    <div class="row-left">
                        <p class="title-info">DC COMICS</p>
                        <ul class="ul-info">
                            <li class="list-info"><a href="">Characters</a></li>
                            <li class="list-info"><a href="">Comics</a></li>
                            <li class="list-info"><a href="">Movies</a></li>
                            <li class="list-info"><a href="">TV</a></li>
                            <li class="list-info"><a href="">Games</a></li>
                            <li class="list-info"><a href="">Videos</a></li>
                            <li class="list-info"><a href="">News</a></li>
                        </ul>
                        <p class="shop title-info">SHOP</p>
                        <ul class="ul-info">
                            <li class="list-info"><a href="">Shop DC</a></li>
                            <li class="list-info"><a href="">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    <div class="row-center">
                        <p class="title-info">DC</p>
                        <ul class="ul-info">
                            <li class="list-info"><a href="">Terms Of Use</a></li>
                            <li class="list-info"><a href="">Privacy policy (New)</a></li>
                            <li class="list-info"><a href="">Ad Choices</a></li>
                            <li class="list-info"><a href="">Advertising</a></li>
                            <li class="list-info"><a href="">Jobs</a></li>
                            <li class="list-info"><a href="">Subscriptions</a></li>
                            <li class="list-info"><a href="">Talent Workshop</a></li>
                            <li class="list-info"><a href="">CPSC Certificates</a></li>
                            <li class="list-info"><a href="">Ratings</a></li>
                            <li class="list-info"><a href="">Shop Help</a></li>
                            <li class="list-info"><a href="">Contacts</a></li>
                        </ul>
                    </div>
                    <div class="row-right">
                        <p class="title-info">SITES</p>
                        <ul class="ul-info">
                            <li class="list-info"><a href="">DC</a></li>
                            <li class="list-info"><a href="">MAD Magazine</a></li>
                            <li class="list-info"><a href="">DC KIds</a></li>
                            <li class="list-info"><a href="">DC Universe</a></li>
                            <li class="list-info"><a href="">DC POwer Visa</a></li>
                        </ul>
                    </div>

                </div>
                <div class="logo-info">
                </div>

            </div>
            
            
        </div>
        <div class="footer-social">
            <div class="social">
                <span class="sign-up"><a href="">SIGN-UP NOW!</a></span>
                <div class="footer-follow">
                    <span class="follows">FOLLOW US</span>
                    <ul class="ul-social">
                        <li class="list-social">
                            <a href=""><img src="../assets/img/footer-facebook.png" alt=""></a>
                        </li> 
                        <li class="list-social">
                            <a href=""><img src="../assets/img/footer-twitter.png" alt=""></a>
                        </li>
                        <li class="list-social">
                            <a href=""><img src="../assets/img/footer-youtube.png" alt=""></a>
                        </li>
                        <li class="list-social">
                            <a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a>  
                        </li>
                        <li class="list-social">
                            <a href=""><img src="../assets/img/footer-periscope.png" alt=""></a>
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
        height: 400px;
    }

    .footer {
        width: 100%;
        height: 80%;
        background: url(../assets/img/footer-bg.jpg);
    }

    .info {
        display: flex;
        width: 70%;
        height: 100%;
        margin: 0 auto;
    }

    .social-info {
        display: flex;
        width: 47%;
        height: 100%;
    }

    .row-left, .row-center, .row-right {
        padding: 2em;
    }

    .title-info {
        color: white;
        font-weight: bold;
    }

    .ul-info {
        list-style: none;
    }

    .list-info a {
        text-decoration: none;
        font-size: 0.6em;
        color: #707b86;
    }

    .shop {
        padding-top: 1em;
    }

    .logo-info {
        width: 52%;
        height: 100%;
        background:  url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position: center;
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

        & a {
            text-decoration: none;
            color: white;
        }
    }

    .ul-social {
        display: flex;
        list-style: none;
    }

    .list-social {
        padding-left: 1em;
    }
</style>