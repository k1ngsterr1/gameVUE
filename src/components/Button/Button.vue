<template lang="">
  <button class="button">{{ text }}</button>
</template>
<script lang="ts">
import { defineComponent } from "vue"; // This line imports the defineComponent function
export default defineComponent({
  name: "Button",
  props: {
    text: {
      type: String,
      required: true,
    },
  },
  methods: {
    handleClick() {
      this.$emit("click");
    },
  },
});
</script>

<style scoped>
.button {
  width: clamp(150px, 15.624vw, 600px);
  height: clamp(27.5px, 2.8644000000000003vw, 110px);
  font-size: clamp(11px, 1.1457600000000001vw, 44px);
  @apply text-gray-900;
  @apply border-green-950;
  @apply bg-green-700;
}
</style>
