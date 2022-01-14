<template>
    <div class="container">
        <div class="contain">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li><a class="active" href="">CHARACTERS</a></li>
            <li><a class="active" href="">COMICS</a></li>
            <li><a class="active" href="">MOVIES</a></li>
            <li><a class="active" href="">TV</a></li>
            <li><a class="active" href="">GAMES</a></li>
            <li><a class="active" href="">COLLECTIBLES</a></li>
            <li><a class="active" href="">VIDEOS</a></li>
            <li><a class="active" href="">FANS</a></li>
            <li><a class="active" href="">NEWS</a></li>
            <li><a class="active" href="">SHOP</a></li>
        </ul>
        </div>
        <div class="img-jumbotron">
            <div class="series"><a href="">CURRENT SERIES</a></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header',
    data() {

    }
}
</script>

<style lang="scss" scoped>
    .container {
        width: 100%;
        height: 100%;
    }
    
    .contain {
        height: 100px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 70%;
        margin: 0 auto;
    }

    img {
        width: 7%;
    }

    ul {
        display: flex;
        list-style: none;
        
       
         li {
            text-decoration: none;
            padding-left: 1em;
            font-size: 0.7em;
            & a {
               text-decoration: none; 
            }
            // &:hover {
            //     color: #0282f9;
            //     padding-bottom: 94%;
            //     border-bottom: 4px solid #0282f9;
            // } 
        }
    }

    .active:hover,
    .active:active {
        color: #0282f9;
        padding-bottom: 39px;
        border-bottom: 4px solid #0282f9;
    }

    .img-jumbotron {
        width: 100%;
        height: 200px;
        background: url(../assets/img/jumbotron.jpg);
        background-size: cover;
        position: relative;
        img {
            width: 100%;
            height: 100%;
        }
    }

    .series {
        display: inline-block;
        padding: 0.5em 1em;
        font-weight: bold;
        color: white;
        background-color: #0282f9;
        position: absolute;
        top: 182px;
        left: 182px;
        & a {
            text-decoration: none;
            color: white;
        }
    }

    @media screen and (max-width: 992px) {
        ul {
            display: none;
        }
    }
    

</style>
