<template>
  <app-header></app-header>
  <div class="container">
    <comp-contact></comp-contact>
  </div>
  <app-footer></app-footer>
</template>

<script>
import compContact from './components/Contact/index_comp.vue';
export default {
  components: {
    compContact
  }
}
</script>