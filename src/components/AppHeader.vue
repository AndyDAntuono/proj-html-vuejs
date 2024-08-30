<script></script>
<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <nav class="navbar navbar-expand-lg bg-body-tertiary">
                        <div class="container-fluid">
                          <a class="navbar-brand" href="#">
                            <img src="../assets/img/avada-marketing-logo.png" alt="avada-marketing-logo.png">
                          </a>
                          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                          </button>
                          <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                                <li class="nav-item ni-hover dropdown">
                                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                        <div class="link-color">Home</div>
                                    </a>
                                    <ul class="dropdown-menu">
                                        <li><a class="dropdown-item" href="#">Action</a></li>
                                        <li><a class="dropdown-item" href="#">Another action</a></li>
                                        <li><hr class="dropdown-divider"></li>
                                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                                    </ul>
                                </li>
                                <li class="nav-item ni-hover dropdown">
                                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                        <div class="link-color">Services</div>
                                    </a>
                                    <ul class="dropdown-menu">
                                        <li><a class="dropdown-item" href="#">Action</a></li>
                                        <li><a class="dropdown-item" href="#">Another action</a></li>
                                        <li><hr class="dropdown-divider"></li>
                                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                                    </ul>
                                </li>
                                <li class="nav-item ni-hover">
                                    <a class="nav-link" href="#">
                                        <div class="link-color">Why us</div>
                                    </a>
                                </li>
                                <li class="nav-item ni-hover">
                                    <a class="nav-link" href="#">
                                        <div class="link-color">Case-studies</div>
                                    </a>
                                </li>
                                <li class="nav-item ni-hover">
                                    <a class="nav-link" href="#">
                                        <div class="link-color">About</div>
                                    </a>
                                </li>
                                <li class="nav-item ni-hover">
                                    <a class="nav-link" href="#">
                                        <div class="link-color">Blog</div>
                                    </a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#"><i class="fa-solid fa-phone"></i>(555) 802-1234</a>
                                </li>
                                <li class="nav-item rounded quotes">
                                    <a class="nav-link" href="#"><div class="quotes-link-color">Free Quotes</div></a> <!--ho dovuto inerire il testo Free Quotes dentro ad un altro div perché altrimenti non mi permetteva di colorarlo secondo il mockup, tutto ciò perché forse bootstrap mi intralciava-->
                                </li>
                            </ul>
                        </div>
                    </div>
                </nav>
                    <!--
                    <div class="header-navbar mb-2">
                        <div class="container-fluid d-flex align-items-center w-100">
                            <div class="logo bg-white w-20 me-2">
                                <img src="../assets/img/avada-marketing-logo.png" alt="avada-marketing-logo.png">
                            </div>
                            <div class="bg-white w-80">
                                <ul class="justify-content-around list-unstyled">
                                    <li class="nav-item">Home</li>
                                    <li class="nav-item">Services</li>
                                    <li class="nav-item">Why us</li>
                                    <li class="nav-item">Case-studies</li>
                                    <li class="nav-item">about</li>
                                    <li class="nav-item">Blog</li>
                                    <li class="nav-item">
                                        <span><i class="fa-solid fa-phone"></i></span>
                                        <span>(555) 802-1234</span>
                                    </li>
                                    <li class="nav-item">Free Quotes</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                -->
                </div>
            </div>
        </div>
    </header>
</template>
<style lang="scss">
    .header-navbar {
        background-color: red;
    };
    .ni-hover:hover {
        color: #f86011;
        border-bottom: 1px solid #f86011;
    };
    .link-color:hover {
        color: #f86011;
    }
    .fa-phone {
        color: #f86011;
    };
    .quotes {
        background-color: #f8ac83;
    };
    .quotes:hover {
        background-color: #f86011;
    };
    .quotes-link-color {
        color: #f86011;
        text-decoration: none;
    };
    .quotes-link-color:hover {
        color: #ffffff;
        text-decoration: none;
    };
</style>