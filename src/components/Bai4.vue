<template>
  <div>
    <h2>Danh sách kết quả</h2>
    <ul>
      <li>{{ num1 }} + {{ num2 }} = {{ add() }}</li>
      <li>{{ num1 }} - {{ num2 }} = {{ subtract() }}</li>
      <li>{{ num1 }} * {{ num2 }} = {{ multiply() }}</li>
      <li>{{ num1 }} / {{ num2 }} = {{ divide() }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      num1: 10, // Giá trị số thứ nhất
      num2: 10  // Giá trị số thứ hai
    };
  },
  methods: {
    add() {
      return this.num1 + this.num2;
    },
    subtract() {
      return this.num1 - this.num2;
    },
    multiply() {
      return this.num1 * this.num2;
    },
    divide() {
      return this.num2 !== 0 ? (this.num1 / this.num2).toFixed(2) : "Không thể chia cho 0";
    }
  }
};
</script>

<style>
h2 {
  font-weight: bold;
}
ul {
  list-style-type: disc;
  padding-left: 20px;
}
li {
  margin: 5px 0;
}
</style>
