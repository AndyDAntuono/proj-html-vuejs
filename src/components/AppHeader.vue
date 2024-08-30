<script></script>
<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="navbar">
                        <div class="logo bg-white w-20 me-2">
                            <img src="../assets/img/avada-marketing-logo.png" alt="avada-marketing-logo.png">
                        </div>
                        <div class="home">
                            <button class="dropbtn">Home 
                              <i class="fa fa-caret-down"></i>
                            </button>
                            <div class="dropdown-content">
                              <a href="#">Link 1</a>
                              <a href="#">Link 2</a>
                              <a href="#">Link 3</a>
                            </div>
                        </div> 
                        <div class="services">
                          <button class="dropbtn">Services 
                            <i class="fa fa-caret-down"></i>
                          </button>
                          <div class="dropdown-content">
                            <a href="#">Link 1</a>
                            <a href="#">Link 2</a>
                            <a href="#">Link 3</a>
                          </div>
                        </div> 
                        <a href="#">Why us</a>
                        <a href="#">Case studies</a>
                        <a href="#">About</a>
                        <a href="#">Blog</a>
                        <a href="#">
                            <span><i class="fa-solid fa-phone me-2"></i></span>
                            <span>(555) 802-1234</span>
                        </a>
                        <a href="#">Free Quote</a>
                      </div>
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
.navbar {
    overflow: hidden;
    background-color: #ffffff;
  }
  
  .navbar a {
    float: left;
    font-size: 16px;
    color: rgb(0, 0, 0);
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  
  .dropdown {
    float: left;
    overflow: hidden;
  }
  
  .dropdown .dropbtn {
    font-size: 16px;  
    border: none;
    outline: none;
    color: rgb(0, 0, 0);
    padding: 14px 16px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
  }
  
  .navbar a:hover, .dropdown:hover .dropbtn {
    color: #f86011;
    border-bottom: 1px solid #f86011;

  }
  
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #ffffff;
    min-width: 160px;
    z-index: 1;
  }
  
  .dropdown-content a {
    float: none;
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
  }
  
  .dropdown-content a:hover {
    background-color: #ddd;
  }
  
  .dropdown:hover .dropdown-content {
    display: block;
  }
/*
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
    */
</style>