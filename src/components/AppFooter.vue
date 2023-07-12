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
        <div class="container-small text-center text-white">
            <div class="fs-3 mb-3 pt-5"> TOUR OUR FACILITIES</div>
            <div class="grey-line"></div>
            <div class="my-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus cumque perferendis maiores
                ducimus!
                Officiis doloremque laudantium nemo autem sit facere, ea ex aut illo</div>
            <div class="row">
                <div class="col">
                    <input type="text" class="form-control bg-transparent border-white text-white" placeholder="First name">
                </div>
                <div class="col">
                    <input type="email" class="form-control bg-transparent border-white text-white" placeholder="email">
                </div>
            </div>
            <div class="row">
                <div class="col py-4">
                    <input type="phone" class="form-control bg-transparent border-white text-white"
                        placeholder="phone number">
                </div>
                <div class="col py-4">
                    <input type="date" class="form-control bg-transparent border-white text-white"
                        placeholder="appontement date">
                </div>
            </div>
            <div class="row">
                <div class="col py-4">
                    <textarea type="text" class="form-control bg-transparent border-white text-white"
                        placeholder="how can we help?"></textarea>
                </div>
            </div>
            <button class="text-white appointment-button">MAKE AN APPOINTMENT</button>
        </div>
    </div>
    <div class="section-7">
        <div class="container-medium text-center">
            <img src="../assets/img/client-logos-1-200x188.png" alt="logo1">
            <img src="../assets/img/client-logos-2-200x188.png" alt="logo2">
            <img src="../assets/img/client-logos-3-200x188.png" alt="logo3">
            <img src="../assets/img/client-logos-4-200x188.png" alt="logo4">
        </div>
    </div>
</template>

<style lang="scss" scoped>
.section-5 {
    height: 400px;
    display: flex;
}

.section-6 {
    height: 600px;
    background-image: url(../assets/img/make-an-appointment.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

.section-7 {
    height: 200px;
    background-image: url(../assets/img/rgb-gradient-bar-for-logo-carrasel.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    justify-content: space-around;
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

textarea {
    background-color: transparent;
    border: 1px solid white;
    color: white;
}

input::placeholder {
    color: white;
}

textarea::placeholder {
    color: white;
}

.appointment-button {
    width: 100%;
    padding: 10px 0;
    background-color: #3bafbf;
    border: 1px solid transparent;
}
</style>