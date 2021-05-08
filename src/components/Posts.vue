<template>
  <div class="card w-100 bg-light my-3" v-for="post in posts" :key="post.id">
    <Post :post="post" />
</div>
</template>

<script>
import Post from './Post'

export default {
    name:'Posts',
    props:{
      posts:Array
    },
    components:{
      Post
    }

}
</script>

<style>

</style>