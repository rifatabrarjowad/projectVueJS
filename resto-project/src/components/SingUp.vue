<template>
  <img class="logo" alt="logo" src="../assets/resto.png" />
  <div><h1>Sing Up!</h1></div>
  <div class="register">
    <input type="text" placeholder="Enter Name" name="" id="" />
    <input type="email" placeholder="Enter Mail" name="" id="" />
    <input type="password" placeholder="Enter Password" name="" id="" />
    <button>Sing Up</button>
  </div>
</template>
<script>
export default {
  name: "SingUp",
};
</script>
<style >
.logo {
  width: 100px;
}
.register input {
  width: 300px;
  height: 40px;
  padding-left: 20px;
  display: block;
  margin-bottom: 30px;
  margin-right: auto;
  margin-left: auto;
  border: 1px solid skyblue;
}
.register button {
  width: 300px;
  height: 40px;
  border: 1px solid skyblue;
  background: skyblue;
  color: #fff;
  cursor: pointer;
}
</style>