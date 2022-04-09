<template>
    <div>
        {{title}}
    </div>
</template>

<script>
    import {
        reactive,
        toRefs,
        onBeforeMount,
        onMounted
    } from 'vue'
    export default {
        name: '',
        setup() {
            const state = reactive({
                title: 'hello kvite!!!!'
            })
            onBeforeMount(() => {})
            onMounted(() => {})
            return {
                ...toRefs(state),
            }

        }
    };
</script>
<style lang='scss' scoped>
</style>