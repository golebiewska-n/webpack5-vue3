<template>
  <div class="layout-app">
    <h1>Vue App</h1>
    {{ env }}
  </div>
</template>

<script>
export default {
  computed: {
    env () {
      return process.env
    }
  }
};
</script>
