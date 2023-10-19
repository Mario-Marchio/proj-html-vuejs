<script></script>

<template>
    <header>
        <div class="d-flex justify-content-between p-5">
            <a href="#">
                <img src="../assets/img/medical_logo_1x_light.png" alt="Logo" class="d-inline-block align-text-top">
            </a>
            <ul class="nav ">
                <li class="nav-item">
                    <a class=" nav-link d-flex align-items-center pt-3 text-acqua" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-white d-flex align-items-center pt-3" href="#">About</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link text-white d-flex align-items-center pt-3 dropdown-toggle" data-bs-toggle="dropdown"
                        href="#" role="button" aria-expanded="false">Departement</a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">General Pratice</a></li>
                        <li><a class="dropdown-item" href="#">Cardiology</a></li>
                        <li><a class="dropdown-item" href="#">Pediatrics</a></li>
                        <li><a class="dropdown-item" href="#">Diabetes Care</a></li>
                        <li><a class="dropdown-item" href="#">Pre-natal Care</a></li>
                        <li><a class="dropdown-item" href="#">Ultrasound Echocardiogram</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-white d-flex align-items-center pt-3 ">Articles</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link text-white d-flex align-items-center  "><button
                            class="rectangular-button linear-gradient">Make
                            appointment</button></a>
                </li>
            </ul>
        </div>
        <div class="container-medium p-5 text-white">
            <div class="fs-1 pb-4">Caraing <span class="text-acqua">For Life</span></div>
            <div class="pb-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Suscipit, itaque fuga libero quae
                sequi quam
                minima officiis inventore nulla
            </div>
            <div class="nav-item ">
                <a class="nav-link d-flex align-items-center  "><button
                        class="change-color rectangular-button linear-gradient">Learn
                        More</button></a>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header {
    background-image: url(../assets/img/header-image-homepage.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 560px;
}


.nav-item .text-acqua {
    color: #3bafbf;
}

.fs-1 .text-acqua {
    color: #3bafbf;
}


button.change-color:hover {
    background-color: #327EC7;
}

.linear-gradient:hover {
    background: rgb(2, 0, 36);
    background: linear-gradient(90deg, rgba(2, 0, 36, 1) 0%, rgba(59, 70, 191, 1) 33%, rgba(51, 108, 199, 1) 66%, rgba(0, 176, 255, 1) 100%);
}
</style>