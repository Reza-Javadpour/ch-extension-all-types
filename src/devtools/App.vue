<!--Make devtools and see in Inspect menu after that follow tabs: console, network, application, ...-->
<template>
  <div>
    Dev Tools
    <hello-world />
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'App',
  components: { HelloWorld }
}
</script>
