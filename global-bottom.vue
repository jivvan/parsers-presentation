<script>
const today = new Date();
const date = `${today.getFullYear()}-${today.getMonth() + 1}-${today.getDate()}`;
</script>

<template>
  <footer
    class="flex text-slate-400 justify-between absolute bottom-2 left-2 right-2 p-2"
  >
    {{ date }}
    <SlideCurrentNo />
  </footer>
</template>
