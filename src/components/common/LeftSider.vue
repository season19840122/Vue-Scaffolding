<template>
    <div class="left-sider">
        <ul>
            <li>
                <i class="iconfont icon-goumai"></i>
                <div>收银</div>
            </li>
            <li>
                <i class="iconfont icon-dianpu"></i>
                <div>店铺</div>
            </li>
            <li>
                <i class="iconfont icon-hanbao"></i>
                <div>商品</div>
            </li>
            <li>
                <i class="iconfont icon-huiyuanqia"></i>
                <div>会员</div>
            </li>
            <li>
                <i class="iconfont icon-zuanshi"></i>
                <div>统计</div>
            </li>
            <li>
                <i class="iconfont icon-shezhi"></i>
                <div>设置</div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'LeftSider'
}
</script>

<style lang="scss">
.iconfont {
    font-size: 24px;
}
.left-sider {
    color:#fff;
    font-size: 12px;
    background: #1D8ce0;
    position: fixed;
    left: 0;
    top: 0;
    height: 100%;
    width: 50px;
    min-width: 50px;
    li {
        text-align: center;
        border-bottom: 1px solid #20a0ff;
        padding: 10px;
        cursor: pointer;
    }
}
</style>
