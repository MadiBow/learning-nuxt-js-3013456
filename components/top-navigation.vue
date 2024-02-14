<script lang="ts" setup>
  let links = [{
    label: "Home",
    to: "/",
  },
  {
    label: "About Me",
    to: "/about"
  }
]

</script>
<template>
  <UHorizontalNavigation :links="links" class="border-b border-gray-200 dark:border-gray-800" />
</template>

<style scoped></style>
