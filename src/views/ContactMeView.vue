<template>
    <div>
        <ContactForm/>
    </div>
</template>

<script>
import ContactForm from '@/components/ContactForm.vue';

    export default {
        components: {
            ContactForm
        }
    }
</script>

<style scoped>
.line{
    height: 6px;
    width: 30%;
    background: #FBC403;
    display: inline-block;
}

</style>