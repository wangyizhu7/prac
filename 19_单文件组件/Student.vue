<template>
    <!-- 组件结构 -->
    <div class="demo">
        <h2>学生姓名：{{name}}</h2>
        <h2>学生年龄：{{age}}</h2>
    </div>
</template>

<script>
    //组件交互
    export default{
        name:'Student',
        data(){
            name:'lk',
            age:18
        }
    }
</script>