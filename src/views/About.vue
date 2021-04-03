<template>
  <div class="about">
    <h1>This is an about page</h1>
    <carousel>

    <img src="https://placeimg.com/200/200/any?1">

    <img src="https://placeimg.com/200/200/any?2">

    <img src="https://placeimg.com/200/200/any?3">

    <img src="https://placeimg.com/200/200/any?4">

  </carousel>
  </div>
</template>

<script>

import carousel from 'vue-owl-carousel'

export default {
    components: { carousel },
}

</script>