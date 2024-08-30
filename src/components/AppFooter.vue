<script></script>
<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="footer-navbar d-flex">
                    <div class="fn_col-45"></div>
                    <div class="fn_col-55"></div>
                    <div class="fn_col-55"></div>
                    <div class="fn_col-55"></div>
                </div>
            </div>
        </div>
    </footer>
</template>
<style lang="scss">
    .footer-navbar {
        background-color: yellow;
        width: 100%;
        height: 500px; /*l'altezza la inserisco temporaneamente solo per impostare gli spazi*/
    };
    .fn_col-45 {
        width: 45%;
        background-color: pink;
        height: 500px;
        margin-right: 10px;
    };
    .fn_col-55 {
        width: calc(55% / 3);
        background-color: rgb(255, 33, 70);
        height: 500px;
        margin-right: 10px;
    }
</style>