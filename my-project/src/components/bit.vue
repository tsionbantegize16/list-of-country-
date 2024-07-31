<script setup>
import{ inject} from 'vue'
let message = inject('message')

</script>
<template>
    {{ message }}
</template>