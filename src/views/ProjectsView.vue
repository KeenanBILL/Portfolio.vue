<template>
    <main class="min-vh-100">

        <h2 class="text-center" style="color:#f2f2f2; margin-top: 2rem;"></h2>

            <div class="container mx-auto mt-4">

                <div class="row">

                    <div v-for="item in projects" :key="item">

                        <div class="col-md-4">
    
                            <div class="card" style="width: 18rem;">
    
                                    <img :src="item.img" class="card-img-top">
    
                                        <div class="card-body">
    
                                        <h5 class="card-title">{{item.name}}</h5>
    
                                        <a :href='item.link' class="proj-btn mr-2"><i class="fas fa-link"></i> Hosted Site</a>
    
                                    <a :href='item.github' class="proj-btn"><i class="fab fa-github"></i> Github</a>
    
                                </div>
    
                            </div>
    
                        </div>
                    </div>

            </div>

        </div>

    </main>
</template>

<script>
export default {
    data(){
        return{
            projects:[
            {
                name: 'Portfolio Draft',
                img: "https://i.postimg.cc/xT6qFszw/Project1.png",
                github: "https://github.com/KeenanBILL/Portfolio.OS",
                link: "https://portfoliokao.netlify.app/"
            },
            {
                name: 'Bootstrap Excercise',
                img: "https://i.postimg.cc/2ycmTKKT/Project2.png",
                github: "https://github.com/KeenanBILL/Keenan_AO",
                link: "https://billytrial.netlify.app/"
            },
            {
                name: 'Portfolio',
                img: "https://i.postimg.cc/rFkYYjkN/Project3.png",
                github: "https://github.com/KeenanBILL/KA_Billy",
                link: "https://keenanao.netlify.app/"
            },
            {
                name: 'E-commerce Site',
                img: "https://i.postimg.cc/xTBq2X65/Project4.png",
                github: "https://github.com/KeenanBILL/Cape_Walkers",
                link: "https://capewalkers.netlify.app/"
            },
            {
                name: 'Calculator',
                img: "https://i.postimg.cc/9FwFJWc7/Project5.png",
                github: "https://github.com/KeenanBILL/Calculator", 
                link: "https://kaocalculator.netlify.app/"
            }
        ]
        }
    }
}
    
</script>

<style scoped>

</style>