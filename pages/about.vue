<template>
  <div class="bground background-gray-100">
<h1>Quotes</h1>

<p>Quotes have the power to encourage, inspire, and motivate people at times of unhappiness and lacking motivation. At such times, reading a few quotes can uplift one's mood and improve the state of mind.</p>
  </div>
</template>
<script setup>
definePageMeta({
    middleware:["auth"]
})
</script>
<style>
.bground{
    background-image: url('https://c4.wallpaperflare.com/wallpaper/796/642/505/quote-inspirational-typography-fan-art-wallpaper-preview.jpg');
    background-size:cover;
    height:100vh;
}
</style>