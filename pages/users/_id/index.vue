<template>
  <h1>A single user, with ID: {{ $route.params.id }}</h1>
</template>

<script>
export default {
  validate(data) {
    // console.log(data);
    // return true;
    /* Validates incomming id to only accept id 1 */
    // return data.params.id == 1;
    /* Validates incomming id to only accept numbers using regex */
    return /^\d+$/.test(data.params.id);
  },
  layout: "users",
};
</script>

<style>
</style>