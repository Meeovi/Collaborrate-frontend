<template>
    <div>
        <notesmenu />

        
    </div>
</template>

<script>
import notesmenu from '../../components/Menus/notesmenu.vue'

export default {
    components: { notesmenu },
}
</script>

<script setup>
    useHead({
        title: ''
    })
</script>