<!-- 导航栏 -->
<template>
  <div id="tab-bar">
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/home.svg" />
      <div>首頁</div>
    </div>
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/category.svg" />
      <div>分类</div>
    </div>
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/cart.svg" />
      <div>购物车</div>
    </div>
    <div class="tab-bar-item">
      <img src="../../assets/img/tabbar/profile.svg" />
      <div>我的</div>
    </div>
  </div>
</template>

<script>
    //这里可以导入其他文件（比如：组件，工具js，第三方插件js，json文件，图片文件等等）
    //例如：import 《组件名称》 from '《组件路径》';

    export default {
        //import引入的组件需要注入到对象中才能使用
        components: {},
        data() {
            //这里存放数据
            return {};
        },
        //监听属性 类似于data概念
        computed: {},
        //监控data中的数据变化
        watch: {},
        //方法集合
        methods: {},
        //生命周期 - 创建完成（可以访问当前this实例）
        created() {},
        //生命周期 - 挂载完成（可以访问DOM元素）
        mounted() {},
        beforeCreate() {}, //生命周期 - 创建之前
        beforeMount() {}, //生命周期 - 挂载之前
        beforeUpdate() {}, //生命周期 - 更新之前
        updated() {}, //生命周期 - 更新之后
        beforeDestroy() {}, //生命周期 - 销毁之前
        destroyed() {}, //生命周期 - 销毁完成
        activated() {} //如果页面有keep-alive缓存功能，这个函数会触发
    };
</script>
<style scoped>
    /* @import url(); 引入公共css类 */
    
    #tab-bar {
        display: flex;
        background-color: #f6f6f6;
        position: fixed;
        left: 0;
        right: 0;
        bottom: 0;
        box-shadow: 0 -2px 2px rgba(100, 100, 100, 0.2);
        font-size: 16px;
    }
    
    .tab-bar-item {
        flex: 1;
        text-align: center;
        height: 49px;
    }
    
    .tab-bar-item img {
        width: 24px;
        height: 24px;
        margin-top: 2px;
        vertical-align: middle;
    }
</style>