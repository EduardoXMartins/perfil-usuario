<script setup>
import { defineProps } from 'vue';
defineProps(["nome", "periodo", "curso"])

</script>

<template>
    <div class="caixa">
        <h2>{{ nome }}</h2>
        <p>{{ curso }}</p>
        <small>{{ periodo }}</small>
    </div>
</template>
<style scaped>
h2 {
    color: blueviolet;
    margin-bottom: 5px;
    margin-top: 0px;
}

p {
    margin-bottom: 2px;
    margin-top: 0;
}



.caixa {
    width: auto;
    margin: 15px 10px;
    padding: 10px;
    border: 1px solid brown;
}
</style>
