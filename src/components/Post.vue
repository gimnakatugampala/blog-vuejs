<template>
   <div class="card-body">
    <h5 class="card-title">{{post.text}}</h5>
    <p class="card-text">{{post.body}}.</p>
    <a href="#" class="btn btn-primary">Button</a>
  </div>
</template>

<script>
export default {
    name:'Post',
    props:{
        post:Object
    }

}
</script>

<style>

</style>