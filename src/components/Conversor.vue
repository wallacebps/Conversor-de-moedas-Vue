<template>
    <div class="conversor">
        <h2>{{ moedaA }} para {{ moedaB }}</h2>
        <input type="text" v-model="moedaA_value" v-bind:placeholder="moedaA">
        <input type="button" value="Converter">
        <h2>{{ moedaB_value }}</h2>
    </div>
</template>

<script>
export default {
    name: "Conversor",
    props: ['moedaA', 'moedaB'],
    data(){
        return{
            moedaA_value: "",
            moedaB_value: 0
        }
    },
    methods: {
        converter(){
            
        }
    }

}
</script>

<style scoped>

</style>