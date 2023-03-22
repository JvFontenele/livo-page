<template>
  <div>
    <button class="btn">
      {{ title }}
      <img class="img" :src="`${icon}`" />
    </button>
  </div>
</template>

<script setup>
const props = defineProps(["title", "icon"]);
</script>

<style scoped>
.btn {
  background: var(--color-btn-header);
  color: var(--color-gray);
  min-width: 172px;
  display: flex;
  height: 42px;
  align-items: center;
  justify-content: center;
  margin: 0;
  border: none;
  border-radius: 60px;
  cursor: pointer;
  margin-left: 10px;
  padding: 15px 10px;
  font-weight: 600;
}

.btn:hover {
  background: var(--color-btn-header-hover);
}
.img {
  width: 20px;
  margin-bottom: 2px;
  margin-left: 10px;
}

@media screen and (max-width: 600px) {
  .btn {
    min-width: 130px;
    font-size: 0.7em;
    padding: 0px 0px;
  }
}

@media screen and (max-width: 400px) {
  .btn {
    min-width: 110px;
    height: 32px;
    font-size: 0.6em;
    padding: 0px 0px;
  }
  .img {
    width: 15px;
    margin-bottom: 2px;
    margin-left: 5px;
  }
}
</style>
