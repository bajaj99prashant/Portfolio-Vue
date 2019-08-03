<template>
    <div class="contact">
        <div class="container">
            <div class="row justify-content-center pb-lg-4">
                <div class="col-lg-6 text-center">
                    <h3 class="cont-title">Let's Get In Touch.</h3>
                </div>
            </div>

            <div class="row justify-content-center my-4">
                <div class="col-lg-6">
                    <p class="cont-para">Interested in working together? Let's get in touch, drop me a mail or give me a call, I am willing to help you in your vision.</p>
                </div>
            </div>

            <div class="row justify-content-around my-2">
                <div class="col-lg-4 my-2 cont-card px-2">
                    <div class="card">
                        <div class="card-body d-flex justify-content-between flex-row">
                            <img src="../assets/mail.png" class="image">
                            <div class="ml-2">
                                <h6 class="mail">prashantbajaj99@gmail.com</h6>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 my-2 cont-card px-2">
                    <div class="card">
                        <div class="card-body d-flex justify-content-between flex-row">
                            <img src="../assets/phone1.png" class="image">
                            <div class="mx-3">
                                <h6>993-593-7650</h6>
                                <h6>844-817-2344</h6>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="row justify-content-around my-2">
                <div class="col-lg-4 my-2 cont-card px-2">
                    <div class="card">
                        <div class="card-body d-flex justify-content-between flex-row">
                            <img src="../assets/address.png" class="image">
                            <div class="ml-5">
                                <h6>JSS Academy Of Technical Education, Noida - 201301</h6>
                            </div>
                        </div>
                    </div>
                </div>  
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Contact'
}
</script>

<style scoped>
.contact {
    min-height: 90vh;
    background-color: #fff;
    overflow-x: hidden;
    padding: 80px 0px;
}
.cont-title {
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
.cont-para {
    font-size: 1.125rem;
    line-height: 1.688rem;
    margin-bottom: 40px;
}
.image {
    width: 50px;
}
.mail {
    line-height: 255%;
}
.cont-card {
    border: 0px;
}
.cont-card:hover {
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.24);
}
.cont-card>.card {
    border: 0px;
}
@media (max-width: 575px) {
    .cont-title {
        font-size: 1.25rem;
        line-height: 1.875rem;
    }
}
</style>
