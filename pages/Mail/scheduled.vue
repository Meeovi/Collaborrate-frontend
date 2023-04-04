<template>
    <div>
        <mailmenu />

        
    </div>
</template>

<script>
import mailmenu from '../../components/Menus/mailmenu.vue'

export default {
    components: { mailmenu },
}
</script>

<script setup>
    useHead({
        title: ''
    })
</script>