<style lang='less' scoped>
  .frame-window {
      position: relative;
      top: 50%;
      width: 60%;
      min-width: 721px;
      height: 650px;
      margin: 70px 20% auto 20%;
      display: block;
  }
  .bg {
    background: url(https://media.guoanfamily.com/notfonud.jpg) no-repeat center;
    background-size: cover;
    margin-top: -20px;
  }
</style>
<template>
    <div class="bodyTop bg">
      <div style="width:100%;height:auto;position:absolute;left:0;top:0;z-index:10">
             <headeNav :NavActived="2"></headeNav>
        </div>
        <iframe class="frame-window" src="https://error.guoanfamily.com/404/404iframe.html" frameborder="0"></iframe>

        <bottom style="z-index:1;"></bottom>
    </div>
</template>
<script>
import headeNav from '~/components/headerNav.vue'
import bottom from '~/components/bottom.vue'
export default {
  data() {
    return {
      
    };
  },
  components:{
    headeNav,
    bottom
  },
  asyncData() {
    
  },
  methods:{
    
  },
  mounted() {}
};
</script>
