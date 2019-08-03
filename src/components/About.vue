<template>
    <div class="about">
        <div class="container">
            <div class="row pb-4 pb-lg-4 justify-content-center">
                <div class="col-lg-6 text-center">
                    <h3 class="title">About Prashant Bajaj</h3>
                </div>
            </div>

            <div class="row justify-content-center mb-4 mt-5">
                <div class="col-lg-6">
                    <p class="about-details">I am a student of computer science &amp; engineering, I am willing to learn new things in web-development and I will seige every oppurtunity to learn.
                        Currently I am learning vue.js and vuex and I have worked on the basics of frontend such as HTML, CSS and JS.
                    </p>
                    <p class="about-details">Apart from learning web development I am pretty much interested in learning linux. Apart from technical stuff I like
                        playing chess and read Personal Development books.
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'About',
    data() {
        return {

        }
    }
}
</script>

<style scoped>
.about {
    min-height: 100vh;
    background: #fafafa;
    padding: 80px 0px;
    overflow-x: hidden;
}
.title {
    font-size: 1.5rem;
    line-height: 2.25rem;
    letter-spacing: 0.125rem;
    font-weight: 600;
    text-transform: uppercase;
    border-bottom: 5px solid #DF292D;
    padding-bottom: 10px;
    display: inline-block;
    font-family: "Montserrat", sans-serif;
}
.about-details {
    font-size: 1.125rem;
    line-height: 1.688rem;
    margin-bottom: 40px;
}
@media (max-width: 575px) {
    .title {
        font-size: 1.25rem;
        line-height: 1.875rem;
    }
}
</style>
