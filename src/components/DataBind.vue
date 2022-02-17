<template>
    <div>
    <h1>Data Binding in vue js</h1>
    <h2 style="white-space:pre-line">{{ message}}</h2>
    <textarea type="text" v-model="message" />
    </div>
</template>

<script>
    export default {
        name:"DataBind",
        data(){
            return{
                message:"Hi"
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>