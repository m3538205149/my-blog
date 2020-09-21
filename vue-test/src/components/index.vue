<template>
    <div>
        <h1>index.vue页面</h1>
    </div>
</template>

<script>
    export default {
        name:"index",
        data() {
            return {
                msg:'参数信息'
            }
        },
        created: {
            change(){
                console.log(1)
            }
        },
    }
</script>

<style scoped>

</style>