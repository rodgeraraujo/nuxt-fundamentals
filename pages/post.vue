<template>
  <div class="container">
    <article>
      <h1 class="title">What is Balut?</h1>
      <p>If someone placed balut on your plate, you might think they were serving you a hardboiled egg. That is, until you cracked it open and a fully intact duck embryo spilled out. Balut, considered a delicacy in many Asian countries, is produced when fertilized duck eggs are placed in warm sunlight. After about eight days, the eggs are held up to the light and checked to ensure that the budding embryo is ready. Then, the eggs are cooked and served with a dash of salt and a few squirts of lemon juice.</p>
    </article>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  line-height: 1.5;
}
article * {
  margin-bottom: 1rem;
}
aside {
  min-width: 280px;
  max-width: 280px;
  padding-left: 2rem;
}
.title {
  font-size: 2rem;
}
body {
  padding: 1rem;
  background: var(--navy);
  color: white;
}
a {
  color: var(--teal-light);
  text-decoration: none;
  transition: all 0.3s ease;
}
a:hover {
  color: var(--teal);
}
.container {
  margin: 0 auto;
  max-width: 900px;
}
.text-xs {
  font-size: 1.2rem;
}
.text-sm {
  font-size: 1.4rem;
}
.text-base {
  font-size: 1.6rem;
}
.text-lg {
  font-size: 1.8rem;
}
.text-xl {
  font-size: 2rem;
}
h1,
h2,
h3,
h4 {
  color: var(--yellow);
}
</style>