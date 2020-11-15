<template>
  <div id="allposts">
    <Breadcrumb />
      <AllPosts />
</div>


</template>



<script>

import AllPosts from '../components/AllPosts.vue'
import Breadcrumb from '../components/layout/breadcrumb'

export default {
  name: 'allposts',
  components: {
    AllPosts,
    Breadcrumb,
  },
}
</script>

<style>
</style>