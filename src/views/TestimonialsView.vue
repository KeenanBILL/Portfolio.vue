<template>
    <div id="testimonials" class="container mt-3 mb-5">

        <div class="post-heading text-center">

                <h3 class="display-4 fw-bold">Testimonials</h3>

            <div class="line my-4"></div>

        </div>

        <div class="row">

            <div class="col-lg-4 d-flex justify-content-center col-md col-12 pb-5">

                <div class="card m-2 cb1 ">

                    <img class="card-img-top">

                        <div class="card-body">

                            <h5 class="card-title text-center">{{item.name}}</h5>

                                <div class="line my-4"></div>

                                    <p class="card-text text-center">{{item.comments}}</p>

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
                    position: 'Colleague',
                    comments: "Keenan is emotionally mature, well-recognized amongst his colleagues & has excellent team work, leadership skills, no conflict with team members. He has excellent conflict resolution skills when conflict arises."
                    },
                    {
                    name: 'Reece Simons',
                    position: 'Colleague',
                    comments: "Keenan displays a consistent work ethic and manages time well; allowing him to continue growing as an individual, helping himself keep up to date and adhere to deadlines."
                    },
                    {
                    name: 'Deno Rautenbach',
                    position: 'Colleague',
                    comments:"Keenan does not waste time. He's a go getter, always busy with something new. A spirit excited by the idea of exploration and learning. His work ethic is cultivated through seer  grit to excite his neurons."
                    },
                    {
                    name: 'Beyonce Daniels',
                    position: 'Colleague',
                    comments: "Keenan Olivier is an ambitous and a hard working young man. He is a fast learner and he is good at what he does."
                    },
                    {
                    name: 'Zoe Daniels',
                    position: 'Colleague',
                    comments: "Keenan is a hard working young man with a big heart. He is organized, efficient and extremely competent with excellent rapport with people of all ages. He communication skills are excellent no matter if you are talking about verbal or written. I highly recommend Keenan Olivier for any position that she may pursue. He would be a valuable asset to your company."
                    },
                    {
                    name: 'Caron Olivier',
                    position: 'Colleague',
                    comments: "Keenan has shown lot of dedication and strives to present himself in the most professional & ethical manner when preparing tasks and presentations. I admire his determination to do the right thing and speak the truth at his best of his ability."
                    }
                ]

            }
        }
    }
</script>

<style scoped>

</style>i