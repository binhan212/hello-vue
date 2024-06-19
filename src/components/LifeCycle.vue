<template>
    <div>
        <h1 v-bind:id="id">Chúng ta sẽ bind (trói buộc) các property (id,class) cho biến nào đó</h1>
        <br>
        <h1 :xyz="abc">Chúng ta sẽ bind (trói buộc) các property (id,class,xyz,...) cho biến nào đó (cách 2)</h1>
        <br>
        <input type="text" :disabled="ipDisible">
        <br>
        <br>
        <input type="text" v-model="arrName[0]">
        <br>
        <br>
        <input type="text" v-model="objName.name1">
    </div>
</template>
<script>
export default{
    name:'LifeCycle',
    data(){
        return{
            id:"abc",
            ipDisible:true,
            arrName:[
                'bình an','thái bình'
            ],
            objName:{
                name1:'12341',
                name2:'ádfasfas'
            }
        }
    }
}
</script>
<style scoped>

</style>