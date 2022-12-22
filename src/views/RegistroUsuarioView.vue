<template>
  <div>
    <base-registro-usuario />
  </div>
</template>

<script>
// @ is an alias to /src
import BaseRegistroUsuario from '@/components/BaseRegistroUsuario.vue'

export default {
  name: 'HomeView',
  components: {
    BaseRegistroUsuario
  }
}
</script>