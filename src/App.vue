<script>
import Lottie from './components/Lottie.vue';
import a1 from './lottiejson/home.json';

export default {
  data() {
    return {
      jsonData: a1,
    };
  },
  components: {
    Lottie,
  },
};
</script>

<template>
  <!-- 使用本地json动画 -->
  <Lottie :jsonData="jsonData" />
  <!-- 使用线上json动画 -->
  <Lottie src="https://assets10.lottiefiles.com/packages/lf20_dyiqnus5.json" />
</template>
