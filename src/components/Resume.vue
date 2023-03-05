<template>
    <div class="post-heading text-center">
    
        <h3 class="display-4 fw-bold">Career</h3>
    
            <div class="line my-4"></div>
    
    </div>
    
    <div class="row mx-5">
    
        <div class="col-sml-4 d-flex justify-content">
    
            <div v-for="item in career" :key="item">
    
                <div class="card m-2 cb1 ">
    
                    <img :src="item.img" class="card-img-top">
    
                        <div class="card-body">
    
                            <h5 class="card-title text-center">{{item.institution}}</h5>
    
                                <div class="line my-4"></div>
    
                                    <h6>{{item.date}}</h6> 
    
                                    <p class="card-text text-center">{{item.specification}}</p>
    
                    </div>
    
                </div>
                
            </div>
    
        </div>
    
    </div>
    
    <div class="post-heading text-center">
    
        <h3 class="display-4 fw-bold">Education</h3>
    
            <div class="line my-4"></div>
    
    </div>
    
    <div class="row mx-5">
    
        <div class="col-sml-4 d-flex justify-content-center">
    
            <div v-for="item in education" :key="item">
    
                <div class="card m-3 mb-5 cb1">
    
                    <img :src="item.img" class="card-img-top justify-content-center">
    
                        <div class="card-body mb-5">
    
                            <h5 class="card-title text-center">{{item.institution}}</h5>
    
                                <div class="line my-4"></div>
    
                                    <h6>{{item.date}}</h6> 
    
                                    <p class="card-text text-center">{{item.specification}}</p>
    
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
                        img: "https://i.postimg.cc/jSfsJCyx/Chrysalis-Academy-logo-Small.jpg",
                        date: 'February 2022 - May 2022',
                        specification: 'I completed an internship in the HR department, that was required for my last project to attain my BBA Degree. I have learnt many skills at the academy which I can apply in my every day life, such as a team-building day I organized for the staff improved my project management skills.'
                        },
                        {
                        institution: 'Amanzi Blue',
                        img: "https://i.postimg.cc/FRNsvmd9/Amaziblue-2.webp",
                        date: 'July 2019 - December 2019',
                        specification: 'At Amanzi Blue I filled many roles, seeing it was a flexible job, I also gained communication skills. The job was casual which taught how to improve my time management, especially juggling between my studies and the job at the time.'
                        },
                        {
                        institution: 'R.B.Schroeder & Sons',
                        img:"https://i.postimg.cc/Y9JF4Pzb/RB-SCHROEDER-SONS-1.jpg",
                        date: 'November 2020 - February 2021',
                        specification: 'Working as a sales associate, gave me a better perspective of selling value & improved my negotiation skills for sure. I also learnt more about marketing in the industry, which gave me opportunity to apply what I learnt in my marketing module.'
                        }
                    ],
                    education:[
                        {
                        institution: 'Excelsior High School',
                        img: "https://i.postimg.cc/hGrR9mvB/Excelsior-HS.jpg",
                        date: '2014 - 2018',
                        specification: 'Matric / Bachelor'
                        },
                        {
                        institution: 'TSIBA Business School',
                        img: "https://i.postimg.cc/pXzWmpf2/TSIBA-LOGO-Stapline-A.png",
                        date: '2019 - 2022',
                        specification: 'Business Bachelor Degree'
                        },
                        {
                        institution: 'Life Choices Academy',
                        img: "https://i.postimg.cc/6p7bzvQZ/Capture.png",
                        date: 'September 2022 - Current',
                        specification: 'Coding'
                        }
                    ]
    
                }
            }
        }
    </script>

<style scoped>
h1, h3, h4{
    font-family: 'Optien';
}

.card{
    width: 95%;
    height: 25rem;
    border-radius: 15px;
    align-items:center;
    max-height: fit-content;
}
.card-body{
    border-radius: 15px;
    
}

img{
    max-width: 200px;
    max-height: 200px;
    height: 195px;
}

.card-img-top{
    height: 180px;
}
</style>