<template>
  <div class="card justify--right">
    <div class="row">
      <div class="column">
        <img
          alt=""
          src="https://pbs.twimg.com/profile_images/1402894430173110274/5zrO8sS5_400x400.jpg"
          class="avatar"
        />
      </div>
      <div class="column">
        <h3 class="p1">Welcome to the world of anime</h3>
        <p class="title">
          Join if you're new to anime or if you're a long time anime fan come
          visit our site.
        </p>
        <p><button>visit us..</button></p>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
img {
  width: 5em;
}
input[type="text"] {
  margin-bottom: 20px;
  padding: 10px;
}
.avatar {
  vertical-align: middle;
  width: 100px;
  height: 100px;
  border-radius: 50%;
}
.p1 {
  font-family: "Times New Roman", Times, serif;
  font-weight: bold;
  color: rgb(248, 122, 122);
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: center;
  padding: 10px;
}
.title {
  color: grey;
  font-size: 18px;
}
button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}
</style>
