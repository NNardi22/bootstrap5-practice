<template>
  <div class="container my-3">
    <div class="row">
      <div class="col-md-4 themed-grid-col">Primero</div>
      <div class="col-md-4 themed-grid-col">
        <Carousel />
      </div>
      <div class="col-md-4 themed-grid-col">Tercero</div>
    </div>
  </div>
</template>

<style>
.themed-grid-col {
  padding-top: 15px;
  padding-bottom: 15px;
  background-color: rgba(86, 61, 124, 0.15);
  border: 1px solid rgba(86, 61, 124, 0.2);
}
</style>

<script>
import Carousel from "~/components/Carousel";

export default {
  components: {
    Carousel,
  },
};
</script>
