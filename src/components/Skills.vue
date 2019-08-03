<template>
    <div class="skills">
        <div class="container">
            <div class="row pb-4 pb-lg-5 justify-content-center">
                <div class="col-lg-6 text-center">
                    <h3 class="skills-title">Prashant Bajaj's Skills</h3>
                </div>
            </div>
        </div>
        <Timeline/>
    </div>
</template>

<script>
import Timeline from './Timeline'

export default {
    name: 'Skills',
    components : {
        Timeline
    },
    data() {
        return {

        }
    }
}
</script>

<style scoped>
.skills {
    min-height: 100vh;
    overflow-x: hidden;
    padding: 80px 0px;
    background: #343a40;
}
.skills-title {
    font-size: 1.5rem;
    line-height: 2.25rem;
    letter-spacing: 0.125rem;
    font-weight: 600;
    color: #fff;
    text-transform: uppercase;
    padding-bottom: 10px;
    display: inline-block;
    font-family: "Montserrat", sans-serif;
}
@media (max-width: 575px) {
    .skills-title {
        font-size: 1.25rem;
        line-height: 1.875rem;
    }
}
</style>
