<template>
<div>
  <the-mask :mask="['(##) ####-####', '(##) #####-####']" />
</div>
</template>

<script>
import {TheMask} from 'vue-the-mask'

export default {
  name: 'InputMaskTel',
  props: {
    mask: Number
  },
  components: {TheMask}
}
</script>

<style>

</style>