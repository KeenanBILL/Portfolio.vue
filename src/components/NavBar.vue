<template>
    
    <nav class="navbar navbar-expand-md">
        
        <div class="container-fluid">
            
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                
                <span class="navbar-toggler-icon"></span>
                
            </button>
            
            <div class="collapse navbar-collapse" id="navbarNav">
                
                <ul class="navbar-nav mx-auto">
                    
                    <li class="nav-item mx-3" >
                        
                        <router-link to="/">Home</router-link>
                        
                    </li>
                    
                    <li class="nav-item mx-3">
                        
                        <router-link to="/about">About</router-link>
                        
                    </li>
                    
                    <li class="nav-item mx-3">
                        
                        <router-link to="/resume">Resume</router-link>
                        
                    </li>
                    
                    <li class="nav-item mx-3">
                        
                        <router-link to="/projects">Projects</router-link>
                        
                    </li>
                    
                    <li class="nav-item mx-3">
                        
                        <router-link to="/testimonials">Testimonials</router-link>
                        
                    </li>
                    
                    <li class="nav-item mx-3">
                        
                        <router-link to="/contact">Contact</router-link>
                        
                    </li>
                    
                </ul>
                
            </div>
            
        </div>

    </nav>

</template>

<script>
    export default {
        
    }
</script>

<style>

.navbar {
    background-color: #90A955;
    border-radius: 20px;
    margin: 15px;
    text-transform: uppercase;
    font-size: 18px;
    font-weight: 700;
    letter-spacing: 0.2rem;
    padding: 20px;
} 

.navbar a {
    font-weight: bold;
    color: #31572C;
    text-decoration: none;
}

.navbar a:hover {
    text-decoration: none;
    color: #FBC403;
}

.navbar a.router-link-exact-active {
    color: #FBC403;
    text-decoration: none;
    
}

</style>