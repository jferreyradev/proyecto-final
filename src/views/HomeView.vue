<template>
  <div>
    <base-login />
  </div>
</template>

<script>
// @ is an alias to /src
import BaseLogin from '@/components/BaseLogin.vue'

export default {
  name: 'HomeView',
  components: {
    BaseLogin
  }
}
</script>
