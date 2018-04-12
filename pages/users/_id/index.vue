<template>
  <p>
    single user {{$route.params.id}}
  </p>
</template>

<script>
export default {
  validate(data) {
    return /^\d+$/.test(data.params.id);
  },
  layout: "users"
};
</script>
