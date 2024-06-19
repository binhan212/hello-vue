<template>
    <div>
        <h2 v-show="isShow">Chức năng ẩn hiện</h2>
        <button @click="isShow=!isShow">Ân/Hiện</button>
    </div>
</template>
<script>
export default{
    data(){
        return {
            isShow:true
        }
    }
}
</script>
<style scoped>

</style>