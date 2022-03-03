<template>
    <div>
        <div>counter: {{counter}}</div>
        <button @click="IncrementCounter()">Increment</button>
    </div>
</template>

<script>
export default {
  data () {
    return {
      counter: 0
    }
  },
  methods: {
    IncrementCounter () {
      this.counter += 1
    }
  }
}
</script>
