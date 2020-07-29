<template>
<div>
 <form-builder type="template"></form-builder>
</div>
</template>

<script>
import FormBuilder from 'v-form-builder';


export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components:{FormBuilder}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
