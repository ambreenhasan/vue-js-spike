<template>
  <div class="bye">
    <div>
      <button v-on:click="counter.count++">You've clicked this button {{ counter.count }} times</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'bye',
  data () {
    return {
      counter: {
        count: 0
      }
    }
  }
}
</script>
