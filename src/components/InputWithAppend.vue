<template>
  <VCard :flat="true">
    <VTextField label="Anything" v-model="value">
      <template #appendInner>
        Edit me
      </template>
    </VTextField>
  </VCard>
</template>

<script>
export default {
  name: "InputWithAppend",
  data(){
    return {
      value: "",
    }
  },
}
</script>

<style scoped>

</style>