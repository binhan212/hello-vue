<template>
    <div id="MenuTest">
        <h5>MENU</h5>
        <input type="text" v-model="name">
        <br>
        Name:{{ name }}
        <br>
        <input type="checkbox" v-model="check"> đồng ý
        <br>
        <div>
            <input type="radio" value="1" v-model="checkRadio"> 1
            <br>
            <input type="radio" value="2" v-model="checkRadio"> 2
            <br>
            <input type="radio" value="3" v-model="checkRadio"> 3
            <br>
            Value: {{ checkRadio }}
        </div>
    </div>
</template>

<script>
export default {
    name:'MenuTest',
    data(){
        return {
            name: "Phí Văn Lò",
            check: true,
            checkRadio: 1
        }
    },
} 
</script>
<script scoped>

</script>