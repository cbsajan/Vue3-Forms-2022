<template>
  <app-header></app-header>
  <div class="container">
    <!-- <comp-contact></comp-contact> -->
    <comp-Validate> </comp-Validate>
  </div>
  <app-footer></app-footer>
</template>

<script>
// import compContact from './components/Contact/index_comp.vue';
import compValidate from './components/Validate/Index-Comp.vue';
export default {
  components: {
    // compContact
    compValidate
  }
}
</script>