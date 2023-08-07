<script setup>
import { onMounted } from 'vue';
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import Rellax from 'rellax'
onMounted(() => {
      let rellax = new Rellax('.rellax');
})
// var rellax = new Rellax('.rellax');

</script>

<template>
  <!-- <div class="rellax">test</div> -->
  <h2>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse sagittis eros et tortor lacinia cursus. Nulla gravida rutrum elit quis pellentesque. Ut interdum ac odio id facilisis. Ut nec lacus pellentesque, feugiat nulla in, scelerisque leo. Duis convallis leo id nulla malesuada varius. Donec vel arcu ornare, aliquam est a, ultrices orci. Curabitur turpis dui, auctor vitae ex eu, aliquet semper tellus. Donec ac felis velit. Phasellus porttitor egestas neque, vel vehicula sem rutrum ut. Mauris eget molestie ipsum. In hac habitasse platea dictumst. Aliquam sit amet mollis augue, eget fermentum dui. Nulla fermentum consequat dignissim. Nulla mattis ut erat quis semper.

    Maecenas nec nibh lacus. Vestibulum pulvinar neque non lacus pulvinar dapibus. Integer egestas eget nunc ut accumsan. Duis efficitur, elit et imperdiet vestibulum, nisl quam fermentum massa, in sagittis ex mi id lacus. Integer vel mollis elit, eget feugiat turpis. Fusce eleifend condimentum purus, nec tempus massa maximus sed. Suspendisse consequat libero a magna interdum, dictum luctus est porta. Mauris convallis quam lorem. Vestibulum tincidunt, purus et venenatis porta, ex justo sagittis ipsum, posuere sagittis mauris sem vitae mi. Aenean at metus non ipsum cursus convallis vel ut mauris. Donec nisl sapien, lobortis ac nisl vel, bibendum efficitur tellus. Quisque auctor magna magna, eu placerat nunc mollis id. Nulla ac augue molestie, finibus libero ac, aliquet urna. Phasellus dapibus nulla sed sollicitudin accumsan. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.
    
    Nullam et risus quis lacus mattis rutrum. Etiam id justo sollicitudin, lacinia libero sed, suscipit sem. Etiam porttitor elit felis, sollicitudin feugiat ipsum bibendum in. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Duis lorem sem, laoreet eget molestie non, eleifend suscipit sapien. Sed orci felis, blandit eu nunc non, suscipit consectetur augue. Vivamus lorem ante, faucibus aliquet egestas quis, gravida vitae ex. Duis porttitor magna sit amet elit placerat molestie. Nam sit amet rutrum tellus, ac tempor lectus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aliquam consectetur, lectus vel mollis consequat, orci nulla convallis justo, sit amet rutrum magna ex quis augue. Nulla nec tincidunt leo. Suspendisse semper tellus in porttitor eleifend.</h2>
  <div class="faces">
    <div>
      <img src="/1.png" alt="" class="rellax" data-rellax-speed="2">
    </div>
    <div>
      <img src="/2.png" alt="" class="rellax" data-rellax-speed="-1">
    </div>
    <div>
      <img src="/3.png" alt="" class="rellax" data-rellax-speed="-2">
    </div>
    <div>
      <img src="/4.png" alt="" class="rellax" data-rellax-speed="2">
    </div>
    <div>
      <img src="/5.png" alt="" class="rellax" data-rellax-speed="-2">
    </div>
    <div>
      <img src="/6.png" alt="" class="rellax" data-rellax-speed="2">
    </div>
    <div>
      <img src="/7.png" alt="" class="rellax" data-rellax-speed="-1">
    </div>
    <div>
      <img src="/8.png" alt="" class="rellax" data-rellax-speed="2">
    </div>
  </div>

  <h2>Maecenas nec nibh lacus. Vestibulum pulvinar neque non lacus pulvinar dapibus. Integer egestas eget nunc ut accumsan. Duis efficitur, elit et imperdiet vestibulum, nisl quam fermentum massa, in sagittis ex mi id lacus. Integer vel mollis elit, eget feugiat turpis. Fusce eleifend condimentum purus, nec tempus massa maximus sed. Suspendisse consequat libero a magna interdum, dictum luctus est porta. Mauris convallis quam lorem. Vestibulum tincidunt, purus et venenatis porta, ex justo sagittis ipsum, posuere sagittis mauris sem vitae mi. Aenean at metus non ipsum cursus convallis vel ut mauris. Donec nisl sapien, lobortis ac nisl vel, bibendum efficitur tellus. Quisque auctor magna magna, eu placerat nunc mollis id. Nulla ac augue molestie, finibus libero ac, aliquet urna. Phasellus dapibus nulla sed sollicitudin accumsan. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.

    Nullam et risus quis lacus mattis rutrum. Etiam id justo sollicitudin, lacinia libero sed, suscipit sem. Etiam porttitor elit felis, sollicitudin feugiat ipsum bibendum in. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Duis lorem sem, laoreet eget molestie non, eleifend suscipit sapien. Sed orci felis, blandit eu nunc non, suscipit consectetur augue. Vivamus lorem ante, faucibus aliquet egestas quis, gravida vitae ex. Duis porttitor magna sit amet elit placerat molestie. Nam sit amet rutrum tellus, ac tempor lectus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aliquam consectetur, lectus vel mollis consequat, orci nulla convallis justo, sit amet rutrum magna ex quis augue. Nulla nec tincidunt leo. Suspendisse semper tellus in porttitor eleifend.
    
    Curabitur a nisi vel lorem sodales pulvinar eget sit amet risus. Nam porttitor consequat commodo. Curabitur vehicula sapien ac quam commodo, vitae convallis odio interdum. Mauris sollicitudin vestibulum urna. Aliquam cursus, est et interdum consectetur, libero risus gravida justo, non consectetur dolor est vitae justo. Vestibulum eleifend tempor euismod. Praesent tincidunt ut neque eleifend faucibus. Vestibulum in odio sit amet felis sollicitudin sollicitudin.
    
    Etiam malesuada massa at dolor sollicitudin eleifend. Integer ipsum nunc, consequat at odio at, posuere hendrerit est. Cras sit amet nibh vel tortor viverra suscipit. Maecenas fringilla mattis molestie. Pellentesque laoreet ex vel dolor suscipit facilisis. Pellentesque porttitor ut justo facilisis tincidunt. Cras sit amet tortor magna. Quisque luctus nisi mollis lorem feugiat malesuada. Fusce tincidunt ut leo in maximus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae</h2>
</template>

<style scoped>

div img {
  display: block;
  max-height: 200px;
  max-width: 100%;
  position: relative;
}

.faces {
  height: 30vw;
  margin-bottom: 100px;
  max-height: 400px;
  position: relative;
  display: flex;
  justify-content: space-between;
}

.faces div:first-child img {
  margin-top: 130%;
  z-index: 1;
}

.faces div:nth-child(2) img {
  margin-left: -25%;
  margin-top: 60%;
}

.faces div:nth-child(3) img {
  margin-left: 25%;
}

.faces div:nth-child(4) img {
  margin-left: -20%;
  margin-top: 100%;
}

.faces div:nth-child(5) img {
  margin-left: 10%;
  margin-top: 25%;
}

.faces div:nth-child(6) img {
  margin-left: -20%;
  margin-top: 60%;
}


.faces div:nth-child(8) img {
  margin-left: -20%;
  margin-top: 100%;
}
</style>
