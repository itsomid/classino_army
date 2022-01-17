<template>
    <swiper :options="swiperOption" ref="mySwiper">
        <!-- slides -->

        <swiper-slide>
            <div class="main_slide">
                <h1>کنکور یه میدون جنگه و کلاسینو قوی‌ترین سلاح این جنگ</h1>
                <p style="text-align: center;font-weight: 600;">اگه آدم این جنگی، به ارتش کلاسینو خوش‌اومدی!</p>
                <p>کنکور دشمنیه که باید در برابرش، یک جنگجوی حرفه‌ای باشی و یادبگیری که چجوری شکستش بدی.</p>
                <p>کلاسینو برای جنگجوهای کنکوری سلاح‌هایی رو آماده کرده تا بتونن تو این جنگ پیروز بشن؛ آیا می‌دونین
                    سلاح‌های کلاسینو چی هستند؟</p>
                <img class="banner" src="../assets/images/campaign/banner.png">
            </div>

        </swiper-slide>
        <swiper-slide>
            <div class="main_slide">
                <h1> سلاح‌هایی که کلاسینو در اختیارتون قرار میده</h1>
                <div class="row_slide2">
                    <div class="item">
                        <img src="../assets/images/campaign/farmande2.png">
                        <p><span>فرماندهان جنگ:</span> بهترین اساتید ایران در این جنگ همراه شما هستن و مسیر رو به شما
                            نشون میدن.</p>
                    </div>
                    <div class="item">
                        <img src="../assets/images/campaign/separ.png">
                        <p><span>سپر هزینه:</span> این سلاح‌ رو با کمترین هزینه و حتی پرداخت قسطی در اختیارتون قرار
                            میدیم.</p>
                    </div>

                </div>
                <div class="row_slide2">
                    <div class="item">
                        <img src="../assets/images/campaign/otagh.png">
                        <p><span>اتاق فکر جنگ: </span>در کلاسینو با جنگجوهای کنکوری در ارتباط خواهید بود و می‌تونین با
                            فرماندهان (اساتید) ارتش هم ارتباط مستقیم داشته باشین.</p>
                    </div>
                </div>
                <div class="row_slide2">
                    <div class="item">
                        <img src="../assets/images/campaign/bomb.png">
                        <p><span>بمب ذخیره‌ی زمان: </span>با این سلاح از همین الان تا روز کنکور، می‌تونین حدود ۲ ماه
                            زمان بیشتر ذخیره کنین.</p>
                    </div>
                    <div class="item">
                        <img src="../assets/images/campaign/sangar.png">
                        <p><span>امن‌ترین سنگرت: </span>خونت هر جای ایران که باشه می‌تونی به کلاسینو دسترسی داشته باشی و
                            به صورت زنده تو کلاس‌ها شرکت کنی.</p>
                    </div>
                </div>
            </div>
        </swiper-slide>
        <swiper-slide>
            <div class="main_slide">
                <h1>فرماندهان کلاسینو که همیشه پیروز این جنگ بودن</h1>
                <p>در کلاسینو بهترین اساتید ایران رو دو هم جمعن تا شما بتونین به بهترین شکل، تاکتیک‌ها و مهارت‌های جنگِ
                    با کنکور رو یاد بگیرین و تو شکستش موفق بشین.</p>

                <img class="asatid" src="../assets/images/campaign/asatid2.png">
            </div>
        </swiper-slide>
        <swiper-slide>
            <div class="main_slide">
                <h1>مدال‌داران کلاسینو</h1>
                <p>در سال گذشته برای اولین بار در ایران، کلاس‌های کنکور توسط کلاسینو به صورت آنلاین برگزار شد و خیلی از
                    افرادی که به ارتش کلاسینو اعتماد کردن، تونستن در جنگ با کنکور موفق بشن؛ در ادامه اسامی تعدادی از این
                    قهرمانا اورده شده.</p>
                <div class="row_slide2 rank">
                    <div>
                        <img src="../assets/images/campaign/pouya-ebrahimi.jpg">
                        <p>پویا ابراهیمی</p>
                        <p class="rotbe">رتبه ۹۹ - رشته ریاضی</p>
                    </div>
                    <div >
                        <img src="../assets/images/campaign/hosein-eskandari-nia.jpg">
                        <p>حسین اسکندری نیا</p>
                        <p class="rotbe">رتبه ۲۲ - رشته تجربی</p>
                    </div>
                    <div >
                        <img src="../assets/images/campaign/taha-tabari-nia.jpg">
                        <p>طاها طبری نیا</p>
                        <p class="rotbe">رتبه ۸۱ - رشته تجربی</p>
                    </div>
                </div>

            </div>
        </swiper-slide>
        <div class="swiper-pagination" slot="pagination"></div>
        <div class="swiper-button-prev" slot="button-prev"></div>
        <div class="swiper-button-next" slot="button-next"></div>
    </swiper>
</template>

<script>
    import {swiper, swiperSlide} from 'vue-awesome-swiper'

    export default {
        components: {
            swiper,
            swiperSlide
        },
        data() {
            return {
                swiperOption: {
                    slidesPerView: 1,
                    autoHeight: true,
                    mousewheel: true,
                    navigation: {
                        nextEl: '.swiper-button-next',
                        prevEl: '.swiper-button-prev'
                    },
                    breakpoints: {
                        3000: {
                            direction: 'vertical',
                            pagination: {
                                el: '.swiper-pagination',
                                type: 'bullets',
                                clickable: true
                            }
                        },
                        1200:{
                            direction: 'horizontal',
                        },
                        991: {
                            direction: 'horizontal',

                        },
                    },

                }
            }
        },

    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
    @import "../assets/css/swiper.min.css";
    @import "~bootstrap/scss/functions";
    @import "~bootstrap/scss/variables";
    @import '~bootstrap/scss/mixins/_breakpoints';

    .main_slide {
        padding: 55px 30px;
        max-height: 100%;
        @include media-breakpoint-down(md) {
            margin: 1rem 0;
            padding: 0;

            &:last-of-type {
                margin-bottom: 0;
            }
            &:first-of-type{
                margin-top: 0;
            }
        }

        h1 {
            font-size: 1.7em;
            margin: 15px 0 30px 0;
            font-weight: 600;
            @include media-breakpoint-down(lg) {
                font-size: 1.2em;
                margin: 15px 0;
            }
        }

        > p {
            text-align: right;
            font-size: 1.5em;
            padding: 0 50px;
            font-weight: normal;
            margin-bottom: 30px;
            @include media-breakpoint-down(lg) {
                padding: 0 5px;
                font-size: 1em;
                margin-bottom: 15px;
            }
        }

        .row_slide2 {
            margin-bottom: 2em;
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            @include media-breakpoint-down(md) {
                flex-direction: column;
                margin-bottom: 0;
            }
            &:nth-child(3) {
                .item {
                    width: 70%;
                    @include media-breakpoint-down(md) {
                        width: 100%;
                    }
                }
            }

            .item {
                width: 49%;
                text-align: right;
                display: flex;
                flex-direction: row;
                align-items: flex-start;
                @include media-breakpoint-down(md) {
                    width: 100%;
                }
                img {
                    max-width: 100px;
                    float: right;
                    margin-left: 20px;
                    @include media-breakpoint-down(lg) {
                        max-width: 50px;
                    }

                }
                p{
                    font-size: 1.3em;
                    @include media-breakpoint-down(lg) {
                        font-size: 1em;
                    }
                }
                span {
                    font-weight: 500;
                }

            }

        }

    }

    .row_slide2 {
        &.rank{
            display: flex;
            flex-direction: row;
            @include media-breakpoint-down(lg) {
                div{
                    width: 32%;
                }
            }
            img {
                width: 70%;
                margin-bottom: 10px;
                border: 2px solid #270e4e;
                box-shadow: -3px 5px 8px 3px #343a404f;
                @include media-breakpoint-down(md) {
                    width: 65%;
                }
                @include media-breakpoint-only(lg) {
                    width: 60%;
                }
            }

            p {
                font-weight: 600;
                font-size: 1.3em;
                &.rotbe{
                    font-size: 1.3em;
                }
                @include media-breakpoint-down(lg) {
                    font-size: .8em;
                    &.rotbe{
                        font-size: .9em;
                    }
                }

            }
        }


    }

    @include media-breakpoint-up(xl) {
        .swiper-container, .swiper-slide, .swiper-wrapper {
            height: 100% !important;
        }
        .swiper-slide {
            overflow: hidden;
        }
    }
    @include media-breakpoint-only(lg){
        /*.swiper-container, .swiper-slide, .swiper-wrapper {*/
        /*    height: auto !important;*/
        /*}*/
        .swiper-container{
            height: auto !important;
        }
        .swiper-slide {
            overflow: hidden;
        }
    }

    .swiper-button-prev {
        background-image: url("../assets/images/campaign/hand-drawn-up.svg") !important;
        top: 20px;
        right: calc(50% - 30px) !important;
        background-size: 60px;
        width: 60px;
        @include media-breakpoint-down(lg){
            background-size: 40px;
            right: calc(50% - 20px) !important;
        }
    }

    .swiper-button-next {
        background-image: url("../assets/images/campaign/hand-drawn-down.svg") !important;
        top: 96%;
        right: calc(50% - 30px) !important;
        background-size: 60px;
        width: 60px;
        @include media-breakpoint-down(lg){
            background-size: 40px;
            right: calc(50% - 20px) !important;
        }
    }

    .asatid {
        width: 60%;
        @include media-breakpoint-down(md) {
            width: 90%;

        }
    }
    .banner{
        width: 90%;
        margin-top: 20px;
        @include media-breakpoint-down(lg) {
            margin-top: 20px;
            width: 100%;
            margin-bottom: 20px;
        }
    }

</style>
