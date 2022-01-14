<template>
  <div class="slide">
      <img :src="srcImage" alt="">
      <p>{{ tipeSeries }}</p>
  </div>
</template>

<script>
export default {
    name: 'Slide',
    props: [
        'srcImage',
        'tipeSeries'
    ]
}
</script>

<style lang="scss" scoped>

.slide {
    width: 180px;
    height: 180px;
    margin: 10px;
    margin-bottom: 30px;
    img {
        width: 100%;
        height: 100%;
    }
    p {
        color: white;
    }
}
   

</style>