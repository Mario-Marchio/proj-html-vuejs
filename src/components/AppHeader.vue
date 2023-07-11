<script></script>

<template>
    <header>
        <div class="d-flex justify-content-between p-5">
            <a href="#">
                <img src="../assets/img/medical_logo_1x_light.png" alt="Logo" class="d-inline-block align-text-top">
            </a>
            <ul class="nav ">
                <li class="nav-item">
                    <a class="nav-link  d-flex align-items-center pt-3 text-acqua" aria-current="page" href="#">Home</a>
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
                    <a class="nav-link text-white d-flex align-items-center  "><button class="rectangular-button">Make
                            appointment</button></a>
                </li>
            </ul>
        </div>
    </header>
</template>

<style>
header {
    background-image: url(../assets/img/header-image-homepage.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 800px;
}

.rectangular-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #3bafbf;
    color: #fff;
    border: none;
    border-radius: 0;
}

.text-acqua {
    color: #3bafbf;
}
</style>