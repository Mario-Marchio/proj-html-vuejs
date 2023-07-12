<script></script>

<template>
    <div class="section-5">
        <div class="container-small text-center text-white bgc-l-blue footer-header">
            <div class="fs-3 mb-3">Emergency care</div>
            <img class="img-wave" src="../assets/img/wave-divider.png" alt="wave">
            <div class="grey-line"></div>
            <div class="m-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus cumque perferendis
                maiores
            </div>
            <a><button class=" text-white button-border1">Learn More</button></a>
        </div>
        <div class="container-small text-center text-white bgc-l-blue2 footer-header">
            <div class="fs-3 mb-3"> Expert diagnostics</div>
            <img class="img-wave" src="../assets/img/wave-divider.png" alt="wave">
            <div class="grey-line"></div>
            <div class="m-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus cumque perferendis
                maiores
            </div>
            <a><button class=" text-white button-border2">Learn More</button></a>
        </div>
        <div class="container-small text-center text-white bgc-l-blue3 footer-header">
            <div class="fs-3 mb-3"> Superb rehabilitation</div>
            <img class="img-wave" src="../assets/img/wave-divider.png" alt="wave">
            <div class="grey-line"></div>
            <div class="m-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus cumque perferendis
                maiores
            </div>
            <a><button class=" text-white button-border3">Learn More</button></a>
        </div>
    </div>
    <div class="section-6">

    </div>
    <div class="section-7">

    </div>
</template>

<style>
.section-5 {
    height: 400px;
    display: flex;
}

.section-6 {
    height: 800px;
    background-image: url(../assets/img/make-an-appointment.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

.section-7 {
    height: 300px;
    background-image: url(../assets/img/rgb-gradient-bar-for-logo-carrasel.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}


.bgc-l-blue {
    background-color: #3bafbf;
    flex-basis: calc(100% / 3);
}

.bgc-l-blue2 {
    background-color: #3896c2;
    flex-basis: calc(100% / 3);
}

.bgc-l-blue3 {
    background-color: #327ecf;
    flex-basis: calc(100% / 3);
}

.footer-header {
    justify-content: center;
    display: flex;
    flex-direction: column;
}

.img-wave {
    width: 70px;
    margin-left: 280px
}

.button-border1 {
    padding: 10px 20px;
    background-color: #3bafbf;
    border: 1px solid white;
}

.button-border2 {
    padding: 10px 20px;
    background-color: #3896c2;
    border: 1px solid white;
}

.button-border3 {
    padding: 10px 20px;
    background-color: #327ecf;
    border: 1px solid white;
}
</style>