<template>
    <div class="contact">

        <h1>Contact Me</h1>

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
    background: rgb(0, 200, 77);
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