<template>
  <div>
    <h1>V-Model</h1>
    <input v-model="massage" />
    <h3>{{ massage }}</h3>
  </div>
</template>>



<script>
export default {
  data() {
    return {
      massage: "",
    };
  },
};
</script>>