<template>
    <div class="container">
        <div class="contain">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li><a href="">CHARACTERS</a></li>
            <li><a class="active" href="">COMICS</a></li>
            <li><a href="">MOVIES</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">GAMES</a></li>
            <li><a href="">COLLECTIBLES</a></li>
            <li><a href="">VIDEOS</a></li>
            <li><a href="">FANS</a></li>
            <li><a href="">NEWS</a></li>
            <li><a href="">SHOP</a></li>
        </ul>
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
        height: 100px;
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
        }
    }

    .active {
        color: #0282f9;
        padding-bottom: 94%;
        border-bottom: 4px solid #0282f9;
    }
    

</style>
