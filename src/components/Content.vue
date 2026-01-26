<script setup></script>

<template>
  <div class="content">
    <section>
      <div class="main">
        <h2>"<i>First,</i> Solve the problem.Then, write the code "</h2>
        <sub> - John Johnson</sub>
      </div>

      <button>Another !</button>
    </section>
  </div>
</template>

<style scoped>
.content {
  display: flex;
  align-items: center;
  justify-content: center;
}

section {
  border-top-right-radius: 20px;
  border-bottom-left-radius: 20px;
  background-color: rgba(197, 200, 200, 0.877);
  display: flex;
  gap: 4rem;
  align-items: center;
  justify-content: center;
  padding: 3rem 0rem;
  flex-direction: column;
}

main {
  position: relative;
}

sub {
  position: absolute;
  right: 50%;
}

h2 {
  text-align: center;
  width: 40%;
}

button {
  font-size: 1.2rem;
  font-weight: 500;
  border: none;
  padding: 5px;
  border-radius: 3px;
  color: whitesmoke;
  background-color: rgba(20, 139, 139, 0.779);
}
</style>
