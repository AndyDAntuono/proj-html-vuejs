<script>
export default {
    data() {
        return {
          links: [
            {
              label: 'Home ',
              url: '#',
              current: true
            },
            {
              label: 'Services',
              url: '#',
              current: false
            },
            {
              label: 'Why us',
              url: '#',
              current: false
            },
            {
              label: 'Case studies',
              url: '#',
              current: false
            },
            {
              label: 'Blog',
              url: '#',
              current: false
            },
          ]
        }
    }
}
</script>
<template>
  <header>
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="navbar">
              <div class="logo bg-white w-20 me-2">
                <a href="#">
                  <img src="../assets/img/avada-marketing-logo.png" alt="avada-marketing-logo.png">
                </a>
              </div>
              <div v-for="link, index in links" :key="index" :class="['nav-item', link.current ? 'active' : '']">
                <a class="nav-link" :href="link.url">{{ link.label }}</a>
              </div>
              <!--
              <div class="nav-item">
                <a class="nav-link" href="#">Home <i class="fa-solid fa-chevron-down"></i></a>
              </div>
              <div class="nav-item">
                <a class="nav-link" href="#">Services <i class="fa-solid fa-chevron-down"></i></a>
              </div>
              <div class="nav-item">
                <a class="nav-link" href="#">Why us</a>
              </div>
              <div class="nav-item">
                <a class="nav-link" href="#">Case studies</a>
              </div>
              <div class="nav-item">
                <a class="nav-link" href="#">Blog</a>
              </div>
              -->
              <div>
                <span><i class="fa-solid fa-phone me-2"></i></span>
                <span>(555) 802-1234</span>
              </div>
              <div class="quotes rounded nav-item">
                <a class="nav-link" href="#">Free Quote</a>
              </div>
            </div>
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

    .nav-item.active .nav-link {
      color: #f86011;
      border-bottom: 1px solid #f86011;
  }

    .navbar .nav-link:hover {
      color: #f86011;
      border-bottom: 1px solid #f86011;
    }

    .fa-phone {
      color: #f86011;
    }

    .quotes {
        background-color: #f8ac83;
        color: #f86011;
        padding: 1px;
        width: 100px;
        text-align: center;
     }

    .quotes:hover {
        background-color: #f86011;
    };
    .quotes:hover .nav-link {
      color: #ffffff;
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