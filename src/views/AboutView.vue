<template>
  <div class="about">
    <h1>Project Description</h1>
    <p>
      This project aim to creat an AI chat bot using the
      <a href="https://groq.com/">Groq</a> API.
    </p>
  </div>
</template>

<style>
.about {
  display: flex;
  flex-direction: column;
  align-items: center;
}
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    justify-content: center;
  }
}
</style>
