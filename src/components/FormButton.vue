<template>
        <div class="col-auto">
          <button class="btn btn-primary mb-3">{{ props.buttonText }}</button>
        </div>
</template>

<script>
const props = defineProps ({
    buttonText: {
        type: String,
        required: true,
    },
})
    
</script>

<style scoped>

</style>