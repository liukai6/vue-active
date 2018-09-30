<template>
  <div>
    nihao
    <mt-button @click="btn" type="default">default</mt-button>
  </div>
</template>
<script>
import { Toast } from 'mint-ui'
export default {
  name: 'Index',
  data () {
    return {}
  },
  methods: {
    btn () {
      Toast({
        message: 'Upload Complete',
        iconClass: 'mint-toast-icon mintui mintui-field-warning',
        duration: 5000
      })
    }
  }
}
</script>
<style>
  .mintui-field-warning {
    font-size: 30px;
  }
</style>
