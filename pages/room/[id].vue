<script setup>
const route = useRoute();
const routr = useRouter();
</script>

<template>
  <div>
    <h2>房型詳細頁面</h2>
    <h3>
      {{ route.fullPath }}
    </h3>
    <button @click="routr.go(-1)">回上一頁</button>
  </div>
</template>

<style scoped></style>