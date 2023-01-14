<template>
    <div class="post-heading text-center">

        <h3 class="display-4 fw-bold">Contact</h3>

    <div class="line my-4"></div>

</div>

    <div>

        <form action="https://formspree.io/f/xeqdpbpb" method="POST">

            <label>First Name<input name="fname" type="text" placeholder="Enter your Name" required></label>

            <label>Surname<input name="sname" type="text" placeholder="Enter your Surname" required></label>

            <label>Company<input name="cname" type="text" placeholder="Company" required></label>
            
            <label>Email Address<input name="email" type="email" placeholder="Enter your Email Address" required></label>
            
            <label><textarea name="message" type="message" placeholder="Comments" required></textarea></label>

            <button>Submit</button>

        </form>

    </div>

</template>

<script>

    export default {
    }
    
</script>

<style scoped>

form input{
    display: flex;
    flex-direction: row;
    margin: auto;
    justify-content: space-between;
    width: 60%;
    height: 30px;
    border: solid 2px #31572C;
    border-radius: 20px;
    text-align: center;
}
textarea{
    border:#31572C;
    border-radius: 20px;
    width: 60%;
}
button{
    width: 25%;
    height: 30px;
    border-radius: 20px;
    background: #90A955;
    font-weight: bold;
    border: #31572C;
}
label, input{
    display: block;
}
label{
    margin-bottom: 20px;
    font-weight: bold;
}

line{
    height: 6px;
    width: 30%;
    background: #FBC403;
    display: inline-block;
}

</style>