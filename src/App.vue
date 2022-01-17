<template>
  <div id="app" class="container-fluid">
<!--    <div id="nav">-->
<!--      <router-link to="/">Home</router-link> |-->
<!--      <router-link to="/about">About</router-link>-->
<!--    </div>-->
    <router-view/>
  </div>
</template>

<style >

    /*@import "~bootstrap-v4-rtl/scss/bootstrap-rtl";*/

    @font-face {
        font-family: IranYekan;
        src: url('assets/fonts/iranyekan/iranyekanwebregular.eot');
        src: url('assets/fonts/iranyekan/iranyekanwebregular.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/iranyekan/iranyekanwebregular.woff') format('woff'),
        url('assets/fonts/iranyekan/iranyekanwebregular.ttf') format('truetype');
        font-weight: normal;
    }
    @font-face {
        font-family: IranYekan;
        src: url('assets/fonts/iranyekan/iranyekanwebbold.eot');
        src: url('assets/fonts/iranyekan/iranyekanwebbold.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/iranyekan/iranyekanwebbold.woff') format('woff'),
        url('assets/fonts/iranyekan/iranyekanwebbold.ttf') format('truetype');
        font-weight: 500;
    }
    @font-face {
        font-family: IranYekan;
        src: url('assets/fonts/iranyekan/iranyekanwebextrabold.eot');
        src: url('assets/fonts/iranyekan/iranyekanwebextrabold.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/iranyekan/iranyekanwebextrabold.woff') format('woff'),
        url('assets/fonts/iranyekan/iranyekanwebextrabold.ttf') format('truetype');
        font-weight: 600;

    }
    @font-face {
        font-family: IranYekan;
        src: url('assets/fonts/iranyekan/iranyekanwebblack.eot');
        src: url('assets/fonts/iranyekan/iranyekanwebblack.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/iranyekan/iranyekanwebblack.woff') format('woff'),
        url('assets/fonts/iranyekan/iranyekanwebblack.ttf') format('truetype');
        font-weight: 700;
    }

    @font-face {
        font-family: IranYekan;
        src: url('assets/fonts/iranyekan/iranyekanwebextrablack.eot');
        src: url('assets/fonts/iranyekan/iranyekanwebextrablack.eot?#iefix') format('embedded-opentype'),
        url('assets/fonts/iranyekan/iranyekanwebextrablack.woff') format('woff'),
        url('assets/fonts/iranyekan/iranyekanwebextrablack.ttf') format('truetype');
        font-weight: 800;
    }
</style>
