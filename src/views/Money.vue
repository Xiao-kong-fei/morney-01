<template>
    <layout class-prefix="layout">
        <NumberPad/>
        <Types/>
        <Notes/>
        <Tags/>
    </layout>
</template>

<script lang="ts">
    import NumberPad from '@/components/Money/NumberPad.vue'
    import Types from '@/components/Money/Types.vue'
    import Notes from '@/components/Money/Notes.vue'
    import Tags from '@/components/Money/Tags.vue'
    export default {
    components: { NumberPad, Types, Notes, Tags },
        name: 'Money',
    }
</script>

<style lang="scss">
    .layout-content {
        border: 3px solid red;
        display: flex;
        flex-direction: column-reverse;
    }
</style>