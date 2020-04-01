<template>
  <div>
    Home Screen
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <DiagsReport />
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import DiagsReport from '@/components/DiagsReport.vue'

export default {
  name: 'Home',
  components: {
    DiagsReport
  }
}
</script>
