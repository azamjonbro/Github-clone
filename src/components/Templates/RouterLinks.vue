<template >
    <router-link :to="to" :class="class">{{ title }}</router-link>
        
</template>
<script>
export default {
   props: {
        title: {
            type: String,
            default: 'Home'
        },
        to: {
            type: String,
            default: '/'
        },
        class: {
            type: String,
            default: ''
        },
    },
}
</script>
<style >
    
</style>