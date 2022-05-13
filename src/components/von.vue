<template>
  <div>
    <h1>V-On</h1>
    <h2>{{ massage }}</h2>
    <button v-on:click="add()">Add</button>
  </div>
</template>>


<script>
export default {
  data() {
    return {
      massage: 0,
    };
  },
  methods: {
    add() {
      this.massage = this.massage + 1;
    },
  },
};
</script>>
