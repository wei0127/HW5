<template>
  <title>XReading:Log in to the site</title>
  <div class="box">
    <form>
      <img src="logo.png" alt="xreading">
      <input type="text" name="" placeholder="Username" />
      <input type="password" name="" placeholder="Password" />
      <div class="checkbox"><span class="checkbox-text">Remember username</span></div>
      <br>
      <br>
      <a href="#">Forgotten your username or password?</a>
      <input type="submit" name="" value="         Log in         " />
    </form>
  </div>
</template>

<script>
export default {
  name: "hw3"
}
</script>

<style scoped>
    body {
      margin: 0;
      padding: 0;
      font-size: 13px;
      font-family: sans-serif;
      background: #215b4f;
    }

    .box {
      width: 300px;
      padding: 40px;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: white;
      text-align: center;
    }

    .box input[type="text"],
    .box input[type="password"] {
      border: 0;
      background: #ececec;
      display: block;
      margin: 20px auto;
      text-align: left;
      /*border: 2px solid #3498db;*/
      padding: 10px 10px;
      width: 200px;
      outline: none;
      color: black;
      border-radius: 5px;
      transition: 0.25s;
    }

    .box input[type="submit"] {
      border: 0;
      background: #93c702;
      display: block;
      margin: 20px auto;
      text-align: center;
      /*border: 2px solid #2ecc71;*/
      padding: 10px 30px;
      outline: none;
      color: white;
      border-radius: 5px;
      transition: 0.25s;
      cursor: pointer;
    }

    .box p {
      color: black;
    }

    .box a {
      font-size: 12px;
      color: gray;
      text-decoration: underline;
    }

    .checkbox {
      width: 11px;
      height: 11px;
      background-color: #fff;
      border: 1px solid #999;
      position: absolute;
      top: 252px;
      right: 250px;
      vertical-align: middle;
      margin-left: 5px;
    }

    .checkbox-text {
      white-space: nowrap;
      display: inline-block;
      vertical-align: middle;
      position: absolute;
      color: black;
      margin-left: 15px;
    }
</style>