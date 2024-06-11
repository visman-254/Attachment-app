<!-- layouts/default.vue -->
<template>
    <div class="layout">
        <header class="menu">
            <NuxtLink to="/" class="logo">KVDA</NuxtLink>

            <nav class="nav-bar">
                <NuxtLink to="/login" class="nav-link">Login</NuxtLink>
                <NuxtLink to="/sign-up" class="nav-link">Sign-up</NuxtLink>
            </nav>
        </header>
        <main class="content">
            <slot />
        </main>
        <Footer />
    </div>
</template>

<script setup>
import Footer from '~/components/Footer.vue';
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}
.menu {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    display: flex;
    padding: 20px 100px;
    backdrop-filter: blur(10px);
    justify-content: space-between;
    align-items: center;
    z-index: 1000;
    
   
    
}
.logo {
    font-size: 32px;
    color: rgba(31, 17, 17, 0.664);
    text-decoration: none;
    font-weight: 700;
    
}
.nav-bar a {
    font-size: 18px;
    color: rgba(8, 8, 8, 0.616);
    text-decoration: none;
    font-weight: 500;
    margin-left: 40px;
}
.nav-bar a:hover {
    text-decoration: line-through;
}
.layout {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    padding-top: 80px; 
}
.content {
    flex: 1;
    padding-bottom: 60px; 
}
</style>
