.<template>
    <li class="menu-card">
        <img :src="image" alt="">
        <span><a href="">{{ text }}</a></span>
    </li> 
</template>

<script>
export default {
    name: 'Menu',
    props: [
        'image',
        'text'
    ]
}
</script>

<style lang="scss" scoped>
    .menu-card {
        img {
            height: 45px;
        }
    }
    span {
        font-size: 0.7em;
        padding-left: 0.5em;
        & a {
            text-decoration: none;
            color: white;
        }
    }
</style>