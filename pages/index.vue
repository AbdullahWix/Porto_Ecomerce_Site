<template>
  <div>
    <NavBar/>
    <productView/>
    <featuredProduct/>
    <Component1/>
    <Component2/>
    <Component3/>
    <Component4/>
    <Component5/>
    <footerComponent/>
  </div>
</template>

<script>
import Component1 from '../components/projectComponent/Component_1.vue';
import Component2 from '../components/projectComponent/Component_2.vue';
import Component3 from '../components/projectComponent/Component_3.vue';
import Component4 from '../components/projectComponent/Component_4.vue';
import Component5 from '../components/projectComponent/Component_5.vue';
export default {
  name: 'IndexPage',
  components:{Component1,Component2,Component3,Component4,Component5},
}
</script>

<style lang="css">

@media (min-width: 320px) {
  /* .reverse-sm{
      flex-direction: row-reverse;
      flex-wrap: nowrap;
  } */
}

@media (min-width: 576px) {
  /* .reverse-sm{
      flex-direction: row-reverse;
      flex-wrap: nowrap;
  } */
}

@media (min-width: 768px) {

  }


@media (min-width: 992px) {

  }

@media (min-width: 1200px) {

  }

@media (min-width: 1400px) {

  }

</style>
