<template>
  <div class="box">
    <div class="box1">
        Box1
    </div>
    <div class="box2">
        Box2
    </div>
    <div class="box3">
        Box3
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.box{
    display: flex;
    gap: 20px;
    text-align: center;
    
}
.box1 {
    background-color: red;
    width: 100px;
    height: 100px;
    color: white;
}

.box2 {
    background-color: blue;
    width: 100px;
    height: 100px;
    color: white;

}
.box3 {
    background-color: green;
    width: 100px;
    height: 100px;
    color: white;
 
}

</style>