<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <div class="container">
      <div class="mt-5">
        <button type="button" class="btn btn-barbie-pink me-3">Primary</button>
        <button type="button" class="btn btn-outline-primary">Primary</button>
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>
