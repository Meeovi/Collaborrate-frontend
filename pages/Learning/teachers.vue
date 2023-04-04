<template>
    <div>
        <learningmenu />


    </div>
</template>

<script>
import learningmenu from '../../components/Menus/learningmenu.vue'

export default {
    components: { learningmenu },
}
</script>

<script setup>
    useHead({
        title: ''
    })
</script>