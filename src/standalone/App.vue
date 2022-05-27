<!--Create a standalone to run without browser and install from your website-->
<template>
  <div>
    Stand Alone
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'App',
  components: { HelloWorld }
}
</script>
