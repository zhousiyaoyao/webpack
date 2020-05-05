<template>
    <div id="container">
        <h1>{{initData}}</h1>
    </div>
</template>

<script>
export default{
    data(){
        return{
            initData: 'Vue开发商'
        }
    }
}
</script>

<style scoped>
#container{
    color:red;
    display: flex;
}
</style>