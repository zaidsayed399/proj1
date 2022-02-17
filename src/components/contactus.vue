<template>
    <div class="contact"> 
<h1>Contact Us Component</h1>
    <div class="mb-3">
  <label  class="form-label">Email address</label>
  <input type="email" class="form-control"  placeholder="name@example.com">
</div><br><br>
<div class="mb-3">
  <label  class="form-label">Example textarea</label>
  <textarea class="form-control"  rows="3"></textarea>
</div>
<br><br>
<button type="submit">Submit</button>
    </div>
</template>

<script>
export default {
    name:'contact',
}
</script>
<style scoped>
.contact{

}
</style>

