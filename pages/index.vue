<template>
  <div>
    <Slider />
    <Cart />
  </div>
</template>

<script>
import Cart from '../components/Cart.vue';
import Slider from '../components/Slider.vue';
export default {
    name: "index",
    components: { 
       Slider,
      Cart
     }
}
</script>
