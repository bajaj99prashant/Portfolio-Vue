<template>
    <div class="blue-bg">
        <div class="container">
            <!--first section-->
            <div class="row align-items-center how-it-works">
                <div class="col-2 text-center bottom">
                    <div class="circle">1</div>
                </div>
                <div class="col-6">
                    <h5>Frontend Framework</h5>
                    <p>I've learnt and implemented vue.js, bootstrap-vue and currently I am working on and learning vuex. I've made a chat-app, collection app and my portfolio on vue.js</p>
                </div>
            </div>
            <!--path between 1-2-->
            <div class="row timeline">
                <div class="col-2">
                    <div class="corner top-right"></div>
                </div>
                <div class="col-8">
                    <hr/>
                </div>
                <div class="col-2">
                    <div class="corner left-bottom"></div>
                </div>
            </div>
            <!--second section-->
            <div class="row align-items-center justify-content-end how-it-works">
                <div class="col-6 text-right">
                    <h5>Firebase</h5>
                    <p>I've used database, realtime-database, hosting and deploying facilities of firebase. Currently looking forward to learn user authentications.</p>
                </div>
                <div class="col-2 text-center full">
                    <div class="circle">2</div>
                </div>
            </div>
            <!--path between 2-3-->
            <div class="row timeline">
                <div class="col-2">
                    <div class="corner right-bottom"></div>
                </div>
                <div class="col-8">
                    <hr/>
                </div>
                <div class="col-2">
                    <div class="corner top-left"></div>
                </div>
            </div>
            <!--third section-->
            <div class="row align-items-center how-it-works">
                <div class="col-2 text-center full-left">
                    <div class="circle">3</div>
                </div>
                <div class="col-6">
                    <h5>Javascript and ajax</h5>
                    <p>I am experienced enough in Javascript and ajax, I've learnt constructors, prototypes, inheritance and classes in object oriented programming.</p>
                </div>
            </div>
            <!--path between 3-4-->
            <div class="row timeline">
                <div class="col-2">
                    <div class="corner top-right"></div>
                </div>
                <div class="col-8">
                    <hr/>
                </div>
                <div class="col-2">
                    <div class="corner left-bottom"></div>
                </div>
            </div>
            <!--Fourth section-->
            <div class="row align-items-center justify-content-end how-it-works">
                <div class="col-6 text-right">
                    <h5>Styling and css frameworks</h5>
                    <p>Apart from knowing HTML and CSS, I've gone through docs of SCSS, learnt and implemented Bootstrap.</p>
                </div>
                <div class="col-2 text-center ful">
                    <div class="circle">4</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Timeline',
    data () {
        return{

        }
    }
}
</script>

<style scoped>
.blue-bg {
  font-family: "Montserrat", sans-serif;
  font-weight: 300;
  color: #fff;
  height: 100%;
}

.circle {
  font-weight: bold;
  padding: 15px 20px;
  border-radius: 50%;
  background-color: #DF292D;
  color: #fff;
  max-height: 50px;
  z-index: 2;
}

.how-it-works.row {
  display: flex;
}
.how-it-works.row .col-2 {
  display: inline-flex;
  align-self: stretch;
  align-items: center;
  justify-content: center;
}
.how-it-works.row .col-2::after {
  content: "";
  position: absolute;
  border-left: 3px solid #DF292D;
  z-index: 1;
}
.how-it-works.row .col-2.bottom::after {
  height: 50%;
  left: 50%;
  top: 50%;
}
.how-it-works.row .col-2.full::after {
  height: 100%;
  left: calc(50% - 3px);
}
.how-it-works.row .col-2.top::after {
  height: 50%;
  left: 50%;
  top: 0;
}

.how-it-works.row .col-2.full-left::after {
  height: 100%;
  left: 50%;
  top: 0;
}

.how-it-works.row .col-2.ful::after {
  height:50%;
  left: calc(50% - 3px);
  top: 0;
}

.timeline div {
  padding: 0;
  height: 40px;
}
.timeline hr {
  border-top: 3px solid #DF292D;
  margin: 0;
  top: 17px;
  position: relative;
}
.timeline .col-2 {
  display: flex;
  overflow: hidden;
}
.timeline .corner {
  border: 3px solid #DF292D;
  width: 100%;
  position: relative;
  border-radius: 15px;
}
.timeline .top-right {
  left: 50%;
  top: -50%;
}
.timeline .left-bottom {
  left: -50%;
  top: calc(50% - 3px);
}
.timeline .top-left {
  left: -50%;
  top: -50%;
}
.timeline .right-bottom {
  left: 50%;
  top: calc(50% - 3px);
}
</style>
