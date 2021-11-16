<template>
  <div>
    <div id="printTest">

      　　　　　　<p>锄禾日当午</p>

      　　　　　　<p>汗滴禾下土 </p>

      　　　　　　<p>谁知盘中餐</p>

      　　　　　　<p>粒粒皆辛苦</p>
    </div>

    　　　　<el-button v-print="'#printTest'" type="success">打印</el-button>
  </div>

</template>

<script>
  export default {
    name: "test1",
    data(){
      return{

      }
    }
  }
</script>

<style scoped>
div {
  text-align: center;
}
</style>
