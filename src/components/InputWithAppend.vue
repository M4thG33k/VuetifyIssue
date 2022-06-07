<template>
  <VCard :flat="true">
    <VTextField label="Anything">
      <template #appendInner>
        Edit me
      </template>
    </VTextField>
  </VCard>
</template>

<script>
export default {
  name: "InputWithAppend",
}
</script>

<style scoped>

</style>