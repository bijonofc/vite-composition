<template>
    <div>
        <h2>Hello World</h2>
    </div>
    

</template>

<script setup>
import { useCounter } from '../js/useCounter';

const {count,method}=useCounter();

</script>

<style lang="scss" scoped>

</style>