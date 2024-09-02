<script>
export default {
    data() {
        return {
          links: [
            {
              label: 'Marketing Plan',
              url: '#',
              current: false
              /*0*/
            },
            {
              label: 'Sales Development',
              url: '#',
              current: false
              /*1*/
            },
            {
              label: 'Digital Marketing',
              url: '#',
              current: false
              /*2*/
            },
            {
              label: 'Pricing',
              url: '#',
              current: false
              /*3*/
            },
            {
              label: 'Why Us',
              url: '#',
              current: false
              /*4*/
            },
            {
              label: 'Case Studies',
              url: '#',
              current: false
              /*5*/
            },
            {
              label: 'Learning Center',
              url: '#',
              current: false
              /*6*/
            },
            {
              label: 'Video Turorials',
              url: '#',
              current: false
              /*7*/
            },
            {
              label: 'Customers',
              url: '#',
              current: false
              /*8*/
            },
            {
              label: 'Blog',
              url: '#',
              current: false
              /*9*/
            },
            {
              label: 'Who We Are',
              url: '#',
              current: false
              /*10*/
            },
            {
              label: 'Contact Us',
              url: '#',
              current: false
              /*11*/
            },
            {
              label: 'Careers',
              url: '#',
              current: false
              /*12*/
            }
          ]
        }
    }
}
</script>
<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="footer-navbar d-flex mt-5">
                    <div class="fn-left">
                        <h2>Grow Your Online Business<br> Strategically, and Improve<br> Customer Retention.</h2>
                        <div class="mt-3">
                            <span class="me-3"><a class="footer-icon" href=""><i class="fa-brands fa-facebook-f"></i></a></span>
                            <span class="me-3"><a class="footer-icon" href=""><i class="fa-brands fa-twitter"></i></a></span>
                            <span class="me-3"><a class="footer-icon" href=""><i class="fa-brands fa-instagram"></i></a></span>
                            <span class="me-3"><a class="footer-icon" href=""><i class="fa-brands fa-youtube"></i></a></span>
                            <span class="me-3"><a class="footer-icon" href=""><i class="fa-brands fa-linkedin-in"></i></a></span>
                            <span class="me-3"><a class="footer-icon" href=""><i class="fa-brands fa-tiktok"></i></a></span>
                        </div>
                        <p>&copy; 2020 &#8226; Avada Consulant &#8226; Powered by WordPress</p>
                    </div>
                    <div class="fn-right-l">
                        <h5 class="mb-3">Services</h5>
                        <ul class="list-unstyled">
                            <li v-for="link, index in links.slice(0, 6)" :key="index" :class="['mb-3', link.current ? 'active' : '']">
                                <a :href="link.url">{{ link.label }}</a>
                            </li>
                            <!--
                            <li class="mb-3">Marketing Plan</li>
                            <li class="mb-3">Sales Development</li>
                            <li class="mb-3">Digital Marketing</li>
                            <li class="mb-3">Pricing</li>
                            <li class="mb-3">Why Us</li>
                            <li class="mb-3">Case Studies</li>
                            -->
                        </ul>
                        <p class="mt-5">Call Us (555) 802-1234</p>
                    </div>
                    <div class="fn-right-c">
                        <h5 class="mb-3">Resources</h5>
                        <ul class="list-unstyled">
                            <li v-for="link, index in links.slice(6, 10)" :key="index" :class="['mb-3', link.current ? 'active' : '']">
                                <a :href="link.url">{{ link.label }}</a>
                            </li>
                            <!--
                            <li class="mb-3">Learning Center</li>
                            <li class="mb-3">Video Turorials</li>
                            <li class="mb-3">Customers</li>
                            <li class="mb-3">Blog</li>
                            -->
                        </ul>
                    </div>
                    <div class="fn-right-r">
                        <h5 class="mb-3">Company</h5>
                        <ul class="list-unstyled">
                            <li v-for="link, index in links.slice(10)" :key="index" :class="['mb-3', link.current ? 'active' : '']">
                                <a :href="link.url">{{ link.label }}</a>
                            </li>
                            <!--
                            <li class="mb-3">Who We Are</li>
                            <li class="mb-3">Contact Us</li>
                            <li class="mb-3">Careers</li>
                        -->
                        </ul>
                        <p>info@yourcompany.com</p>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<style lang="scss">
    .footer-navbar {
        width: 100%;
    };
    .footer-icon {
        color: #000000,
    };
    .fn-left {
        width: 45%;
        margin-right: 10px;
    };
    .fn-left p {
        margin-top: 150px;
    };
    .fn-right-l, .fn-right-c, .fn-right-r {
        width: calc(55% / 3);
        margin-right: 10px;
    };
    .fn-right-l p{
        margin-top: 40px;
    };
    .fn-right-r p{
        margin-top: 160px;
    };
    li a {
        color: #000000;
        text-decoration: none;
    }
    /*la seguente classe l'ho realizzata basandomi all'effetto applicato sul sito originale, Avada Consulant*/
    ul a:hover {
        color: #f86011;
        border-right: 1px solid #f86011;
        padding-right: 75px;
    }
</style>