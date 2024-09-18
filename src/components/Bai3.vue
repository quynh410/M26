<template>
 <div class="card">
  <div class="card-image">Image</div>
  <div class="card-title">Title</div>
  <button class="card-button">Add to card</button>
</div>

</template>

<script>
export default {

}
</script>

<style>
.card {
  width: 200px;
  border: 1px solid #ddd;
  border-radius: 10px;
  overflow: hidden;
  text-align: center;
  font-family: Arial, sans-serif;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.card-image {
  background-color: #ccc;
  color: black;
  padding: 40px 0;
  font-size: 16px;
}

.card-title {
  padding: 15px;
  background-color: white;
  font-size: 18px;
  color:black;
}

.card-button {
  background-color: white;
  border: 1px solid #ddd;
  padding: 10px;
  cursor: pointer;
  width: 100%;
  transition: background-color 0.3s ease;
}

.card-button:hover {
  background-color: #f0f0f0;
}

</style>