<template>
  <div class="main">
    <nav-bar/>
    <div class="post-layout">
      <div class="row">
        <div class="col-sm">
          <!-- Sidebar -->
        </div>
        <div class="col-sm">
          <post/>
        </div>
        <div class="col-sm">
          <!-- chat box -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from '~/components/Header'
import Post from '~/components/Post'
export default {
  components: {
    NavBar,
    Post
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
}
.main {
  margin: 0;
  min-height: 100vh;
  display: block;
  background-color: #f1f2f5;

  .post-layout {
    display: flex;
  }
}
</style>
