<template>
  <div>
    <img src='../assets/logo.png'>
    <h1>{{ title }}</h1>
    <p>{{ content }}</p>
</template>

<script>
export default {
  name: 'art',
  data () {
    return {
      image: '../assets/logo.png',
      title: 'title',
      content: 'content content content content content content content content content content ' +
               'content content content content content content content content content content ' +
               'content content content content content content content content content content ' +
               'content content content content content content content content content content ' +
               'content content content content content content content content content content ' +
               'content content content content content content content content content content '
    }
  }
}
</script>
