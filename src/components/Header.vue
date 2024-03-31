<script>
import router from "@/router/index.js";

export default {
  data() {
    return {}
  }
};
</script>

<template>
  <header>
    <div class="left">
      <img src="../assets/UP_Bild_with_BG.png">
      <div class="text">
        <h1>UniquePixels</h1>
        <span>in Development</span>
      </div>
    </div>
    <a href="https://discord.com/redirect">
      <div class="module-border-wrap">
        <div class="right">
          <button>Join Discord</button>
        </div>
      </div>
    </a>
  </header>
</template>

<style scoped>
header {
  display: flex;
  padding: 20px;
  background: #0F0F0F;
  justify-content: space-between;
  align-items: center;
}

header a {
  text-decoration: none;
}

.left {
  display: flex;
}

.right {
  display: flex;
}

.right button:hover {
  background-color: #212121;
}
.right button {
  transition: 0.5s;
}

.right button {
  font-size: 20px;
  background-color: #0F0F0F;
  color: white;
  padding: 10px;
  border: 0px solid red;
  border-radius: 0px;
  box-shadow: none;
}

.module-border-wrap {
  max-width: 250px;
  padding: 1rem;
  position: relative;
  background: linear-gradient(to right, red, purple);
  padding: 3px;
}

.module-border-wrap:hover, .right:hover, button:hover {
  cursor: pointer;
}

.text {
  padding: 20px;
}

.text h1 {
  font-size: 40px;
}

.text span {
  font-style: italic;
}

header img {
  width: 120px;
  height: auto;
  border: 2px solid var(--gray);
  box-shadow: rgba(73, 73, 73, 0.22) 3px 3px;
  border-radius: 15px;
}
</style>