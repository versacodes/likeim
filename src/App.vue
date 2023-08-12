<script setup>
import TheHeader from './components/TheHeader.vue'
import BaseInput from './components/BaseInput.vue'
import BaseButton from './components/BaseButton.vue'
</script>

<template>
  <TheHeader/>
  
  <main class="main-container">
    <h1 class="main-title">Personal Collection Of Images Online</h1>
    <p class="main-par">Search and save your favorite photos in your gallery.</p>
    <div class="search-container">
      <BaseInput
        type="search"
        placeholder="Enter search keyword"
        class="search-input"
      />
      <BaseButton
        name="Search"
        class="search-button"
      />
    </div>
  </main>
</template>

<style scoped>
.main-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #fcd;
  padding: 3rem 2rem;
}

.main-title {
  color: #333;
  margin-bottom: 1rem;
  text-align: center;
  font-size: 1.4rem;
}

.main-par {
  font-size: 0.8rem;
  margin-bottom: 2rem;
  text-align: center;
  line-height: 1.7;
}

.search-container {
  display: flex;
  flex-wrap: wrap;
}

.search-input {
  border: 1px solid #444;
  padding: 10px;
  display: inline-block;
  width: 100%;
  font-size: 0.6rem;
}

.search-button {
  font-size: 0.7rem;
  padding: 10.5px;
  width: 100%;
  display: inline-block;
  vertical-align: bottom;
}
</style>
