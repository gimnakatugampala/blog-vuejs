<template>
   <div class="card-body">
    <h5 class="card-title">{{post.text}}</h5>
    <p class="card-text">{{post.body}}.</p>
    <Tags :tags="post.tags"/>
  </div>
</template>

<script>
import Tags from './Tags'
export default {
    name:'Post',
    props:{
        post:Object
    },
    components:{
        Tags
    }

}
</script>

<style>

</style>