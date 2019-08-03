<template>
  <div id="app">
    <Navbar/>
    <Hero/>
    <About/>
    <Skills/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Contact from './components/Contact'
import Navbar from './components/Navbar'
import Hero from './components/Hero'
import About from './components/About'
import Skills from './components/Skills'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Navbar,
    Hero,
    About,
    Skills,
    Contact,
    Footer
  },
  data(){
    return {

    }
  }
}
</script>

<style>
body, html{
  padding: 0;
  margin: 0;
  height: 100%;
  overflow-x: hidden;
}
body::-webkit-scrollbar {
    width: 3px;
}
body::-webkit-scrollbar-thumb {
    background: #DF292D;
}
body::-webkit-scrollbar-track {
    background: #fff;
}
</style>
