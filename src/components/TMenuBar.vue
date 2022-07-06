<template>
  <Menubar>
    <template #start>
      <img
        alt="logo"
        src="https://www.primefaces.org/wp-content/uploads/2020/05/placeholder.png"
        height="40"
        class="mr-2"
      />
    </template>
    <template #end> HELLO </template>
  </Menubar>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    const items = ref([
      {
        label: "File",
      },
    ]);
    return { items };
  },
};
</script>