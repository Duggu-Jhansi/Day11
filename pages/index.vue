<template>
    <div class="bg">
  <h1>Quotes</h1>
  <ContentDoc/>
 </div>
  </template>
  <script setup>
  definePageMeta({
    middleware:["auth"]
})
  </script>
  <style>
  .bg{
      background-image: url('https://c4.wallpaperflare.com/wallpaper/146/520/914/quotes-windows-hd-download-wallpaper-preview.jpg');
      background-size:cover;
      height:100vh;
  }
  </style>