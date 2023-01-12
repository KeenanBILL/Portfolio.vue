<template>
<div id="about" class="container mt-3 pb-5">

    <div class="post-heading text-center">

        <h3 class="display-4 fw-bold">About Me</h3>

            <div class="line my-4"></div>

    </div>

    <div class="row">

        <div class="col-lg-6 col-md-6 col-12">

            </div>

        <div class="col-lg-6 col-md-6 col-12">

            <h2>Get to know me.</h2>
            
            <hr>

                <p>I am always striving to learn new skills & over the past three years studying, working part-time has taught me valuable skills, that I am able to incorporate in my career. I am a God fearing individual that is hungry for happiness from others. Making others happy is what drives me to be ambitious & devoted to be an advocate of change regardless if I make a minor impact. When storms and trails come, I will try my best to be there to lift your head up. Doing this I hope people also acquire the value of resilience in their life.
            </p>

            <button class="btn1">

                <a href="#">Download CV</a>

            </button>

        </div>

    </div>

</div>

<div class="row">

    <div class="col-lg-4 d-flex justify-content-center col-md col-12 pb-5">

        <div v-for="item in testimonials" :key="item">

            <div class="card m-2 cb1 ">

                <img :src="item.img" class="card-img-top">

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
                career:[
                    {
                    institution: 'Chrysalis Academy',
                    date: 'February 2022 - May 2022',
                    specification: 'I completed an internship in the HR department, that was required for my last project to attain my BBA Degree. I have learnt many skills at the academy which I can apply in my every day life, such as a team-building day I organized for the staff improved my project management skills.'
                    },
                    {
                    institution: 'Amanzi Blue',
                    date: 'July 2019 - December 2019',
                    specification: 'At Amanzi Blue I filled many roles, seeing it was a flexible job, I also gained communication skills. The job was casual which taught how to improve my time management, especially juggling between my studies and the job at the time.'
                    },
                    {
                    institution: 'R.B.Schroeder & Sons',
                    date: 'November 2020 - February 2021',
                    specification: 'Working as a sales associate, gave me a better perspective of selling value & improved my negotiation skills for sure. I also learnt more about marketing in the industry, which gave me opportunity to apply what I learnt in my marketing module.'
                    }
                ]
                education:[
                    {
                    institution: 'Excelsior High School',
                    date: '2014 - 2018',
                    specification: 'Matric / Bachelor'
                    },
                    {
                    institution: 'TSIBA Business School',
                    date: '2019 - 2022',
                    specification: 'Business Bachelor Degree'
                    },
                    {
                    institution: 'Life Choices Academy',
                    date: 'September 2022 - Current',
                    specification: 'Coding'
                    }
                ]

            }
        }
    }
</script>

<style>

</style>
