<template>
  <div class="demo">
    <h2>学校名称：{{ name }}</h2>
    <h2>学校地址：{{ address }}</h2>
    <button @click="showName">点我提示学校名</button>
  </div>
</template>
<script>
// export default Vue.extend() 简写为配置对象
export default {
  name: "School", //指定在Vue开发者工具中的组件名
  data() {
    return {
      name: "少林寺",
      address: "河南",
    };
  },
  methods: {
    showName() {
      alert(this.name);
    },
  },
};
</script>
<style>
.demo {
  background-color: antiquewhite;
}
</style>