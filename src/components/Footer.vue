<template>
    <div class="footer">
        <hr>
        <div class="text-center py-4">
            <span class="footer-text">Made with Vue.js and Bootstrap-Vue.</span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer',
    data () {
        return {

        }
    }
}
</script>

<style scoped>
.footer {
    height: 12vh;
}
hr {
    width: 80%;
    margin: auto;
}
.footer-text {
    font-size: 0.75rem;
    line-height: 1.125rem;
    color: #666666;
    letter-spacing: 0.0625rem;
    font-weight: 600;
    font-family: "Montserrat", sans-serif;
    text-transform: uppercase;
}
</style>
