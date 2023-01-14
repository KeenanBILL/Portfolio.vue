<template>
    <main class="min-vh-100">

        <div class="post-heading text-center">

            <h3 class="display-4 fw-bold">Projects</h3>

                <div class="line my-4"></div>

        </div>

        <h2 class="text-center"></h2>

            <div class="container">

                <div class="row justify-content-center">

                    <div v-for="item in projects" :key="item">

                        <div class="col-lg d-flex justify-content-center pb-3">
    
                            <div class="card mb-5">
    
                                    <img :src="item.img" class="card-img-top">
    
                                        <div class="card-body">
    
                                        <h5 class="card-title">{{item.name}}</h5>
    
                                        <a :href='item.link' class="proj-btn mr-2"><i class="bi bi-globe2"></i></a>
    
                                    <a :href='item.github' class="proj-btn"><i class="bi bi-github"></i></a>
    
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
            },
            {
                name: 'Grid Example',
                img: "https://i.postimg.cc/GpprYhMm/Grid.png",
                github: "https://github.com/KeenanBILL/GridExample", 
                link: "https://golden-buttercream-a1eb66.netlify.app/"
            }
        ]
        }
    }
}
    
</script>

<style scoped>
.card{
    max-width: 75%;
    border-radius: 15px;
}

.card-body{
    border-radius: 15px;
}

.line{
    height: 6px;
    width: 30%;
    background: #FBC403;
    display: inline-block;
}

.proj-btn{
    border: 2px solid transparent;
    padding: 10px;
    background: #90A955;
    border-radius: 20px;
    margin-top: 10px;
    width: 40%;
    color: #31572c;
    margin-left: 10px;
}

.proj-btn a{
    text-decoration: none;
    font-size: 1em;
    font-weight: bold;
    text-transform: uppercase;

}
.proj-btn:hover{
    color: #FBC403;
}
</style>