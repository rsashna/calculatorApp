<template>
  <div class="calculator">
    <div class="display">0.3334554</div>
    <div class="btn">C</div>
    <div class="operator">+/-</div>
    <div class="operator">%</div>
    <div class="btn operator">/</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">9</div>
    <div class="btn operator">X</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn operator">-</div>
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn operator">+</div>
    <div class="zero btn">0</div>
    <div class="btn">.</div>
    <div class="btn operator">=</div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.calculator{
  font-size:30px;
display: grid;
grid-template-columns: repeat(4, 1fr);
grid-auto-rows: minimax(50px, auto);
}
.display{
background-color: lightblue;
grid-column: 1 / 5;
}
.zero{
background-color: lightgreen;
grid-column: 1 / 3;
}

.btn{
  background-color: #eee;
  border: 1px solid #333;
}

.operator{
  background-color: lightgreen;
  color: white;
  border: 1px solid #333;
}
</style>
