<template>
  <div class="container my-5">
      <h1>Create Post</h1>
<form>
  <div class="mb-3">
    <label for="text" class="form-label">Text</label>
    <input type="text" class="form-control" id="text" name="text">
  </div>
  <div class="mb-3">
    <label for="body" class="form-label">Body</label>
      <textarea class="form-control" placeholder="Whats in your Mind" id="body" name="body"></textarea>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
  </div>
</template>

<script>
export default {
    name:'AddPost'

}
</script>

<style>

</style>