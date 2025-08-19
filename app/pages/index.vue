<script lang="ts">
import { Component, Vue, Prop } from 'vue-facing-decorator'

@Component()
class Comp extends Vue {
    @Prop()
    prop!: number

    method() { return '' }

    field1 = 'Test1'
    field2 = 'Test2'
}
</script>

<template>{{ field1 }}</template>
