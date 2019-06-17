<template>
    <div>{{ remaining }} item(s) left</div>
</template>


<script>
export default {
    name: 'todo-remaining',
    computed: {
        remaining() {
            return this.$store.getters.remaining
        }
    }
}
</script>

