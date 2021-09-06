<template>
  <main>
    <div class="credit">
      <h1>Made by {{ author }}</h1>
      <p>Vue JS CLI</p>
    </div>
  </main>
</template>

<script>
export default {
  name: "Hero",
  data() {
    return {
      author: "Forklein",
    };
  },
};
</script>

<style>
.credit {
  padding: 20px;
  font-style: italic;
}
</style>