<script setup lang="ts">
import Flicking from '@egjs/vue3-flicking'
import '@egjs/vue3-flicking/dist/flicking.css'

const options = { align: 'prev', circular: true }
</script>

<template>
  <Flicking
    :options="options"
    class="transform -skew-y-12 rotate-12"
  >
    <div style="padding: 1em; width: 50%; background-color:#ddd;">1</div>
    <div style="padding: 1em; width: 50%; background-color:#aaa;">2</div>
    <div style="padding: 1em; width: 50%; background-color:#ddd;">3</div>
  </Flicking>
</template>
