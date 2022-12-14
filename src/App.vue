<template>
  <section>
    <app-header />
    <router-view/>
  </section>
</template>

<script>


// import { store } from './store/store'
import appHeader from './cmps/app-header.vue'
// import { userService } from './services/user.service'


export default {

  created() {
    
  },
  components: {
    appHeader,
  
  },
}
</script>