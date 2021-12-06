<template>
  <div>
    <!-- vetur使用<+v快捷生成vue文件结构 -->
    <!-- template必须有唯一根元素 -->
    <school></school>
    <student></student>
  </div>
</template>
<script>
  import School from "./School"; //脚手架中vue后缀可不写
  import Student from "./Student.vue";
  export default {
    name: "App",
    components: {
      School,
      Student,
    },
  };
</script>

<style>
</style>