<template>
    <div>
        <customersmenu />

        
    </div>
</template>

<script>
import customersmenu from '../../components/Menus/customersmenu.vue'

export default {
    components: { customersmenu },
}
</script>

<script setup>
    useHead({
        title: ''
    })
</script>