<template>
  <h4>Ooops there is an error:</h4>
  <p>{{ error }}</p>
</template>

<script>
export default {
  props: ['error']
}
</script>
