<template>
  <div class="new-page" :style="`min-height: ${layoutMinHeight}px`">
    <h1>{{message}}</h1>
  </div>
</template>

<script lang="ts">
import { Vue, Component, Prop, Watch, Emit, Ref } from "vue-property-decorator";

@Component
export default class extends Vue {
    message: string = "演示页面";
}
</script>

<style scoped lang="less">
</style>