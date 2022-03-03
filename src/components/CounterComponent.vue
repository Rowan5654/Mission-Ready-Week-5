<template>
    <div>
        <div>counter: {{counter}}</div>
        <button @click="IncrementCounter">Increment</button>
    </div>
</template>

<script>
export default {
  data: () => ({
    counter: 0,
  methods: {
    IncrementCounter() {
      counter += 1
    }
  }
  })
}
</script>
