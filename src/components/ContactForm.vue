<template>
    <div class="post-heading text-center">

        <h3 class="display-4 fw-bold">Contact</h3>

    <div class="line my-4"></div>

</div>

    <div>

        <form action="">

            <label>First Name<input type="text" placeholder="Enter your Name"></label>

            <label>Surname<input type="text" placeholder="Enter your Surname"></label>

            <label>Contact Details<input type="text" placeholder="Enter your Contact"></label>

            <label>Email Address<input type="text" placeholder="Enter your Email Address"></label>

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
    width: 30%;
    height: 30px;
    border: solid 2px;
    border-radius: 20px;
    text-align: center;
}
button{
    width: 25%;
    height: 30px;
    border-radius: 20px;
    background: #90A955;
    font-weight: bold;
}
label, input{
    display: block;
}
label{
    margin-bottom: 20px;
    font-weight: bold;
}



</style>