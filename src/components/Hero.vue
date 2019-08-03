<template>
  
    <div class="hero">
        <div class="overlay">
            <div class="container mask">
              <div class="row h-100 d-flex align-content-center">
                <div class="col-lg-9">
                  <h2 class="main-head mt-3">
                    <span>Hi, <br> I am prashant bajaj.</span>
                  </h2>
                  <span class="intro my-5">I am a frontend developer.</span>
                  <span class="d-block breaker mt-4"></span>
                </div>
              </div>
            </div>
        </div>
    </div>
  
</template>

<script>
export default {
  name: 'Hero',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hero {
  background-image: url('../assets/design.jpg');
  height: 100vh;
  background-position: top right;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
  overflow-x: hidden;
}
.mask {
  height: 100%;
}
.overlay {
  height: 100%;
  background: rgba(62, 62, 68, 0.8);
}
.main-head{
  text-transform: uppercase;
  color: white;
  font-size: 4.375rem;
  line-height: 4.375rem;
  font-family: "Montserrat", sans-serif;
  font-weight: 700;
}
.intro{
  font-size: 1rem;
  line-height: 1.5rem;
  color: #ffffff;
  opacity: 0.95;
  letter-spacing: 0.125rem;
  font-weight: 600;
  font-family: "Montserrat", sans-serif;
  text-transform: uppercase;
}
.breaker {
  width: 80px;
  height: 8px;
  background-color: #DF292D;
}
@media (max-width: 575px){
  .main-head {
      font-size: 2.25rem;
      line-height: 2.925rem;
  }
}
@media (max-width: 767px){
  .main-head {
      font-size: 3.125rem;
      line-height: 4.062rem;
  }
}
</style>
