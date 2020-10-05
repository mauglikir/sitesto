<template>
    <div class="content-sto-wrapper">
       <h2>{{msg}}</h2>
    </div>
</template>

<script>
export default {
    name:'content-sto-wrapper',
    commponent:'',
    props: {},
    data(){
        return{
            msg: 'Hello'
        }
    },
    computed:{},
    methods:{}
}
</script>>

<style>
.content-sto-wrapper{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
}
</style>>