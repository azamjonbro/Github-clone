<template >
    <label :for="id" v-if="label">{{ label }}</label>
    <input :type="type" placeholder="placeholder" :value="value" :name="name" :id="id" :class="class" :disabled="disabled" :required="required">
</template>
<script>
export default {
    props: {
        text: {
            type: String,
            default: 'text'
        },
        type: {
            type: String,
            default: 'text'
        },
        placeholder: {
            type: String,
            default: 'Enter text'
        },
        value: {
            type: String,
            default: ''
        },
        name: {
            type: String,
            default: 'input'
        },
        id: {
            type: String,
            default: 'input'
        },
        class: {
            type: String,
            default: ''
        },
        disabled: {
            type: Boolean,
            default: false
        },
        required: {
            type: Boolean,
            default: false
        },
        label: {
            type: String,
        },
    },
}
</script>
<style >
    
</style>