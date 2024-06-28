<script setup>
import CardComp from './CardComp.vue'
</script>

<template>
    <div class="card">
        <p><CardComp name="lucas" position="Admin"></CardComp></p>
        <p><CardComp name="bigsam" position="Admin"></CardComp></p>
        <div >
            <li v-for-list="lists">
                <CardComp name="{{list.name}}" position="{{list.position}}"></CardComp>
            </li>
        </div>

    </div>
    
</template>


<script>
export default {
    components : {
        CardComp, 
    },

}
</script>


<style scoped>
.card{
    margin: 20px;
    margin-left: 0px;
    margin-right: 0px;

}
</style>