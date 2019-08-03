<template>
    <div class="navbar1">
        <b-navbar toggleable="lg" type="dark" :class="padd" :variant="bg">
            <div class="container">
                <b-navbar-brand href="#" class="txt"><span class="text-main">Prashant</span> Bajaj</b-navbar-brand>

                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

                <b-collapse id="nav-collapse" is-nav>
                    <b-navbar-nav class="ml-auto" right>
                        <b-nav-item href="#" class="mx-4 active"><span class="linka">About</span></b-nav-item>
                        <b-nav-item href="#" class="mx-4 active"><span class="linka">Skills</span></b-nav-item>
                        <b-nav-item href="#" class="mx-4 active"><span class="linka">Contact</span></b-nav-item>
                        <b-nav-item href="#" class="mx-4 active"><span class="linka">LinkedIn</span></b-nav-item>
                        <b-nav-item href="#" class="mx-4 active"><span class="linka">Github</span></b-nav-item>
                    </b-navbar-nav>
                </b-collapse>
            </div>
        </b-navbar>
        <hr class="my-0">
    </div>
</template>

<script>
export default {
    name: 'Navbar',
    data () {
        return {
            bg: 'dark',
            padd: 'py-3'
        }
    },
    methods: {

    }
}
</script>

<style scoped>
.txt {
    font-size: 1.9em;
    font-weight: 300;
}
.text-main {
    color: #DF292D;
}
.navbar1 {
    position: fixed;
    top: 0;
    left: 0;
    right: 3px;
    z-index: 1030;
}
.linka::after {
    content: '';
    display: block;
    margin-top: 4px;
    width: 0;
    height: 2px;
    background: #fff;
    transition: width 0.3s;
}
.linka:hover::after {
    width: 100%;
    transition: width 0.3s;
}
</style>
