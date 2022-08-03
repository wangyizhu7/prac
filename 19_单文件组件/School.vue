<template>
    <!-- 组件结构 -->
    <div class="demo">
        <h2>学校名称：{{schoolName}}</h2>
        <h2>学校地址：{{address}}</h2>
        <button @click="showName">点我提示学校名</button>
    </div>
</template>

<script>
    //组件交互
    export default{
        name:'School',
        data(){
            schoolName:'gwu',
            address:'dc'
        },
        methods:{
            showName(){
                alter(this.schoolName)
            }
        }
    }
</script>

<style>
    /* 组件的样式 */
    .demo{
        background-color:orange
    }
</style>