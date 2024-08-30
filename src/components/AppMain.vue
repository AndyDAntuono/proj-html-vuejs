<script></script>
<template>
    <!--per il momento inserisco un impaginazione generica per verificare se l'output generale del progetto corrisponde all'impaginazione che sto impostando-->
    <main>
        <div class="container">
            <!--unlock potential section-->
            <div class="row">
                <div class="unlock-potential d-flex"> <!--volevo inserire l'immagine di sfondo di questa sezione ma manca l'immagine-->
                    <div class="w-50">
                        <h1>Unlock Your Online<br> Growth Potential</h1>
                        <p>
                            Online marketing to secure customer retention,<br> leads, and sales. We focus on the bigger picture.
                        </p>
                        <div class="our-services">Our Services <i class="fa-solid fa-arrow-right"></i></div>
                    </div>
                    <div class="w-50">
                        <div class="card d-flex justify-content-center text-center">
                            <div class="rounded-circle my-2">
                                <img class="rounded-circle" src="../assets/img/marketing-consultant-expert.jpg" alt="">
                            </div>
                            <h3>Richard Madsen</h3>
                            <p>Marketing Consultant Expert</p>
                            <div>
                                <span><i class="fa-solid fa-phone me-2"></i></span>
                                <span>(555) 802-1234</span>
                            </div>
                            <div class="my-2">
                                <input class="w-75" type="text" placeholder="Your Name*">
                            </div>
                            <div class="my-2">
                                <input class="w-75" type="text" placeholder="Your Email*">
                            </div>
                            <div class="my-2">
                                <input class="w-75" type="text" placeholder="Your Phone Number*">
                            </div>
                            <div class="orange-button m-auto rounded w-75 text-center my-2 py-2">Get a Callback</div>
                        </div>
                    </div>
                </div>
            </div>
            <!--services section-->
            <div class="row">
                <div class="col-6">
                    <img src="../assets/img/image-1.png" alt="">
                </div>
                <div class="col-6">
                    <h5>Business Growth</h5>
                    <h1>Increase Brand Awareness</h1>
                    <p>Lorem ipsum dolor sit amet, consectetur adipicing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <div class="orange-button rounded text-center w-25 my-2 py-2">Get a Consultation</div>
                </div>
            </div>
            <div class="row">
                <div class="col-6">
                    <h5>Investors in People</h5>
                    <h1>In-House Sales Training</h1>
                    <p>Lorem ipsum dolor sit amet, consectetur adipicing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <div class="orange-button rounded w-25 text-center my-2 py-2">Get a Consultation</div>
                </div>
                <div class="col-6">
                    <img src="../assets/img/image-2.png" alt="">
                </div>
            </div>
            <div class="row">
                <div class="col-6">
                    <img src="../assets/img/image-3.png" alt="">
                </div>
                <div class="col-6">
                    <h5>Harness Your Social Proof</h5>
                    <h1>Increase Brand Awareness</h1>
                    <p>Lorem ipsum dolor sit amet, consectetur adipicing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis gravida et at massa.</p>
                    <div class="orange-button rounded text-center w-25 my-2 py-2">Get a Consultation</div>
                </div>
            </div>
            <!--brands section-->
            <div class="row">
                <div class="col-12">
                    <div class="text-center m-auto my-5">
                        <h1 class="my-2">Some Brands We Work With</h1>
                        <div>
                            <span>
                                <img src="../assets/img/abstract.png" alt="abstract.png">
                            </span>
                            <span>
                                <img src="../assets/img/cglobal.png" alt="cglobal.png">
                            </span>
                            <span>
                                <img src="../assets/img/next.png" alt="next.png">
                            </span>
                            <span>
                                <img src="../assets/img/hemisferio.png" alt="hemisferio.png">
                            </span>
                            <span>
                                <img src="../assets/img/spaces.png" alt="spaces.png">
                            </span>
                            <span>
                                <img src="../assets/img/digitalbox.png" alt="digitalbox.png">
                            </span>
                        </div>
                    </div>
                </div>
            </div>
            <!--Sandy Reiff section-->
            <div class="row">
                <div class="col-12">
                    <div class="rounded d-flex justify-content-around">
                        <div class="d-flex justify-content-around">
                            <div class="me-1">
                                <img class="rounded-circle w-50" src="../assets/img/marketing-expert-cta.png" alt="">
                            </div>
                            <div>
                                <h3>Sandy Reiff</h3>
                                <p>Marketing Consulant Expert</p>
                            </div>
                        </div>
                        <div>
                            <h2>Drive Leads and Sales with Avada</h2>
                        </div>
                        <div class="sandy-phone rounded"><i class="fa-solid fa-phone me-2"></i>(555) 802-1234</div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>
<style lang="scss">
    .orange-button {
        background-color: #f86011;
        color: #ffffff;
    };
    .sandy-phone {
        background-color: #f8ac83;
        color: #f86011;
        padding: 10px;
        height: 30px;
        display: flex;
        align-items: center;
    }
</style>