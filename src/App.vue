<template>
  <div id="app">
    <router-view></router-view>
    <Nav></Nav>
  </div>
</template>

<script>
import Nav from '@/components/nav'
export default {
  name: 'app',
  components: {
    Nav: Nav
  },
  head: {
    meta: [
      { name: 'viewport', content: 'width=device-width, initial-scale=1'}
    ]
  }
}
</script>
