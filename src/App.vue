<template>
  <div id="app1">
    <router-view />
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 1,
    };
  },
  methods: {
    inc() {
      this.counter += 1;
    },
  },
};
</script>
