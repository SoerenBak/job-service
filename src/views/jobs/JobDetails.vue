<template>
  <h1>Job details page
    <p>Ths job id is: {{ id }}</p>
  </h1>
</template>

<script>
export default {
  data() {
    return {
      id: this.$route.params.id
    }
  }
}
</script>

<style>

</style>