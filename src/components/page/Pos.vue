<template>
    <div class="pos">
       <el-row>
           <el-col :span="8" class="pos-order" id="order-list">
               订单栏
           </el-col>
           <el-col :span="16">
               物品栏
           </el-col>
       </el-row>
    </div>
</template>

<script>
import $ from 'jquery'
export default {
  name: 'Pos',
  mounted: function () {
    var orderHeight = window.innerHeight
    $('#order-list').height(orderHeight)
  }
}
</script>

<style lang="scss">
.pos {
    .pos-order {
        background: #f9fafc;
        border-right: 1px solid #c0ccda;
    }
}
</style>
