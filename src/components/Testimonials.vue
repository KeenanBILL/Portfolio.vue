<template>
    <div id="testimonials" class="container mt-3 mb-5" style="display: inline-block;">

        <div class="post-heading text-center">

                <h3 class="display-4 fw-bold">Testimonials</h3>

            <div class="line my-4"></div>

        </div>

        <div class="row mx-5" >

            <div class="justify-content col-md-4 d-flex">

                <div v-for="item in testimonials" :key="item">

                    <div class="card m-2 cb1 ">
    
                        <img :src="item.img" class="card-img-top">
    
                            <div class="card-body">
    
                                <h5 class="card-title text-center">{{item.name}}</h5>
    
                                    <div class="line my-4"></div>
                                        
                                        <h3>{{item.position}}</h3>
    
                                            <p class="card-text text-center">{{item.comments}}</p>
    
                            </div>
    
                        </div>

                </div>

            </div>

        </div>

    </div>      
</template>

<script>
    export default {
        data() {
            return {
                testimonials:[
                    {
                    name: 'Nabila Samsodien',
                    img: "https://i.postimg.cc/9MnFgyG2/nabila.jpg",
                    position: 'Colleague',
                    comments: "Keenan is emotionally mature, well-recognized amongst his colleagues & has excellent team work, leadership skills, no conflict with team members. He has excellent conflict resolution skills when conflict arises."
                    },
                    {
                    name: 'Reece Simons',
                    img: "https://i.postimg.cc/N0Qh6L2x/reece.jpg",
                    position: 'Colleague',
                    comments: "Keenan displays a consistent work ethic and manages time well; allowing him to continue growing as an individual, helping himself keep up to date and adhere to deadlines."
                    },
                    {
                    name: 'Deno Rautenbach',
                    img: "https://i.postimg.cc/0yxX3F5k/deno.jpg",
                    position: 'Colleague',
                    comments:"Keenan does not waste time, he's a go getter, always busy with something new. A spirit excited by the idea of exploration and learning. His work ethic is cultivated through seer  grit to excite his neurons."
                    },
                    {
                    name: 'Beyonce Leanord',
                    img: "https://i.postimg.cc/kgQHj9xX/IMG-20210606-WA0167.jpg",
                    position: 'Colleague',
                    comments: "Keenan Olivier is an ambitious and a hard working young man. He is a fast learner and he is good at what he does."
                    },
                    {
                    name: 'Zoe Daniels',
                    img: "https://i.postimg.cc/q7CxmGfc/IMG-20221104-090808.jpg",
                    position: 'Colleague',
                    comments: "Keenan is a hard working young man with a big heart. He is organized, efficient and extremely competent with excellent rapport with people of all ages. He communication skills are excellent no matter if you are talking about verbal or written. I highly recommend Keenan Olivier for any position that she may pursue. He would be a valuable asset to your company."
                    },
                    {
                    name: 'Caron Olivier',
                    img: "https://i.postimg.cc/sDR9TWK7/caron-o.jpg",
                    position: 'Colleague',
                    comments: "Keenan has shown lot of dedication and strives to present himself in the most professional & ethical manner when preparing tasks and presentations. I admire his determination to do the right thing and speak the truth at his best of his ability."
                    }
                ]

            }
        }
    }
</script>

<style scoped>
.card-body{
    background-color: #90A955;
    height: 10%;
}
.card{
    width: 95%;
    height: 95%;
    max-height: 670px;
}
.line{
    height: 6px;
    width: 30%;
    background: #FBC403;
    display: inline-block;
}

</style>