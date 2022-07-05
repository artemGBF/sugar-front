<template>
  <div>
    <NavigationBar/>
  </div>
</template>

<script>
import NavigationBar from '../components/NavigationBar'
import 'bootstrap/dist/css/bootstrap.min.css'

export default {
  components: {
    NavigationBar
  },
  data () {
    return {
      test: 'test'
    }
  }
}
</script>

<style scoped>
.test {
  display: none;
}
</style>
