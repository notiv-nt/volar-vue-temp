<template>
  <div>{{ propName }}</div>
  <div>{{ dataName }}</div>
  <div>{{ setupName }}</div>
</template>

<script>
export default {
  props: { propName: String },
  // data: () => ({ dataName: 'hello' }),
  setup: () => ({ setupName: 'here' }),
};
</script>
