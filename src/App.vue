<script setup>

import HeaderComponent from './components/sections/HeaderComponent.vue'
import FooterComponent from './components/sections/FooterComponent.vue'
import IndexView from './views/IndexView.vue';

</script>

<template>
  <div class="container-fluid bg-light p-0">
    <div class="row">
      <div class="col-sm-12 col-md-12 col-lg-12 col-xl-12 col-xxl-12 p-0">

        <div class="row">
          <div class="col-sm-12 col-md-12 col-lg-12 col-xl-12 col-xxl-12 p-0">
            <HeaderComponent/>
          </div>
        </div>

        <!-- <div class="row">
          <div class="col-sm-12 col-md-12 col-lg-12 col-xl-12 col-xxl-12">
            <IndexView />
          </div>
        </div>

        <div class="row">
          <div class="col-sm-12 col-md-12 col-lg-12 col-xl-12 col-xxl-12">
            <FooterComponent/>
          </div>
        </div> -->

      </div>
    </div>
  </div>
</template>

<style scoped></style>



