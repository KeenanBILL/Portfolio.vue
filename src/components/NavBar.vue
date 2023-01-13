<template>
    
    <nav>
        <router-link to="/">Home</router-link> &bull;
        <router-link to="/about">About</router-link> &bull; 
        <router-link to="/resume">Resume</router-link> &bull; 
        <router-link to="/projects">Projects</router-link> &bull; 
        <router-link to="/testimonials">Testimonials</router-link> &bull;
        <router-link to="/contact">Contact</router-link>
    </nav>

</template>

<script>
    export default {
        
    }
</script>

<style>
nav {
    padding: 30px;
    background-color: #90A955;
    border-radius: 20px;
    margin: 15px;
    text-transform: uppercase;
    font-size: 14px;
    font-weight: 700;
    letter-spacing: 0.2rem;
    padding: 20px 0;
} 

nav a {
    font-weight: bold;
    color: #31572C;
    text-decoration: none;
}

nav a:hover {
    text-decoration: none;
    color: #FBC403;
}

nav a.router-link-exact-active {
    color: #FBC403;
    text-decoration: none;
    
}

</style>