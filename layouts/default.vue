<template>
    <main>

        
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">NUXT </NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink>  </li>  
                    <li> <NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/items">Many More.. </NuxtLink></li>
                  
                  
                    
                </ul>
            </nav>
            </header>
        
    
    <div class="container mx-auto p-4">
        <slot/>
    </div>
    </main>

    </template>
    <style scoped>
    .router-link-exact-active{
        color:#bf5700;
    }
</style>