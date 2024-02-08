<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
        <header id="header">
            <h1><a href="#home" class="page-switch"><img src="./dist/img/logo.png" alt="Tyla"></a></h1>
            <div class="social">
                <a href="https://twitter.com/Tyllaaaaaaa" target="_blank"><img src="./dist/img/twitter.png" alt="Twitter"></a>
                <a href="https://www.tiktok.com/@tyla_" target="_blank"><img src="./dist/img/tiktok.png" alt="Tiktok"></a>
                <a href="https://www.instagram.com/tyla/" target="_blank"><img src="./dist/img/insta.png" alt="Instagram"></a>
                <a href="https://www.youtube.com/channel/UC8HOgNWipVorrlBH8oN2R-A" target="_blank"><img src="./dist/img/youtube.png" alt="YouTube"></a>
                <a href="https://www.facebook.com/Tylasings/" target="_blank"><img src="./dist/img/facebook.png" alt="Facebook"></a>
            </div>
        </header>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
