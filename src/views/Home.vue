<template>

    <div class="row">
        <div class="col-lg-3 col-12 mb-lg-0 mb-4 d-none d-lg-block">
            <div class="column one shadow-sm">
                <img class="logo" src="../assets/images/classino_logo_new.png">
                <p><b>به ارتش کلاسینو بپیوندید</b></p>
                <p>با <b>۵۰ هزار</b> تومان اعتبار هدیه</p>
                <form action="https://my.classino.com/register" method="POST">
                    <input type="tel" placeholder="شماره موبایل" @keypress="isNumber($event)">
                    <input type="hidden" name="representer" value="classino_army">
                    <button type="submit" class="btn btn-register mb-3"
                            onclick="gtag('event', 'registerForm', {'event_category': 'army99','event_label': 'register'});">
                        ثبت نام در کلاسینو
                    </button>
                </form>

            </div>
        </div>
        <div class="col-lg-9 col-12 main-content">
            <div class="column two shadow-sm">
                <slider-component class="d-none d-lg-block"></slider-component>
                <div class="d-lg-none">

                    <div class="main_slide">
                        <img class="logo" src="../assets/images/classino_logo_new.png">
                        <h1>کنکور یه میدون جنگه و کلاسینو قوی‌ترین سلاح این جنگ</h1>
                        <p style="text-align: center;font-weight: 600;">اگه آدم این جنگی، به ارتش کلاسینو خوش‌اومدی!</p>
                        <p>کنکور دشمنیه که باید در برابرش، یک جنگجوی حرفه‌ای باشی و یادبگیری که چجوری شکستش بدی.</p>
                        <p>کلاسینو برای جنگجوهای کنکوری سلاح‌هایی رو آماده کرده تا بتونن تو این جنگ پیروز بشن؛ آیا
                            می‌دونین
                            سلاح‌های کلاسینو چی هستند؟</p>
                        <img class="banner" src="../assets/images/campaign/banner.png">
                    </div>
                    <hr class="style-one">
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
                    <hr class="style-one">
                    <div class="main_slide">
                        <h1>فرماندهان کلاسینو که همیشه پیروز این جنگ بودن</h1>
                        <p>در کلاسینو بهترین اساتید ایران رو دو هم جمعن تا شما بتونین به بهترین شکل، تاکتیک‌ها و مهارت‌های جنگِ
                            با کنکور رو یاد بگیرین و تو شکستش موفق بشین.</p>

                        <img class="asatid" src="../assets/images/campaign/asatid2.png">
                    </div>
                    <hr class="style-one">
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
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-12 d-block d-lg-none fixed-column">
            <div class="column one shadow-sm">
<!--                <img class="logo" src="../assets/images/classino_logo_new.png">-->
                <p><b>به ارتش کلاسینو بپیوندید</b></p>
                <p>با <b>۵۰ هزار</b> تومان اعتبار هدیه</p>
                <form action="https://my.classino.com/register" method="POST" class="mobile-form">
                    <input type="tel" class="mobile-input" placeholder="شماره موبایل" @keypress="isNumber($event)">
                    <input type="hidden"  name="representer" value="classino_army">
                    <button type="submit" class="btn mobile-btn-register"
                            onclick="gtag('event', 'registerForm', {'event_category': 'army99','event_label': 'register'});">
                        ثبت نام
                    </button>
                </form>
            </div>
        </div>
    </div>

</template>

<script>
    // @ is an alias to /src

    import SliderComponent from "../components/SliderComponent";

    export default {
        name: 'home',
        components: {
            SliderComponent,
        },
        methods: {
            isNumber: function (evt) {
                evt = (evt) ? evt : window.event;
                var charCode = (evt.which) ? evt.which : evt.keyCode;
                if ((charCode > 31 && (charCode < 48 || charCode > 57))) {
                    evt.preventDefault();
                } else {
                    return true;
                }
            }
        }
    }
</script>
<style lang="scss">

    @import '~bootstrap/scss/bootstrap.scss';
    @import "~bootstrap-v4-rtl/scss/bootstrap-rtl";
    @import "~bootstrap/scss/functions";
    @import "~bootstrap/scss/variables";
    @import '~bootstrap/scss/mixins/_breakpoints';

    html, body {
        height: 100%;
    }

    body {
        font-family: "IranYekan", sans-serif;
        background-image: url("../assets/images/campaign/back-main.png");
        background-size: cover;
        background-repeat: no-repeat;
        padding: 25px 0;
        @include media-breakpoint-down(md) {
            padding: 25px 0;
        }
        @include media-breakpoint-down(md) {
            background-image: url("../assets/images/campaign/classino-mobile.jpg");
            background-size: cover;
            background-attachment: fixed;
        }

    }

    .column {
        background-color: rgba(219, 213, 217, .9);
        border-radius: 5px;
        padding: 10px;
        min-height: 100%;
        height: 94vh;
        @include media-breakpoint-down(md) {
            height: 100%;
        }
        @include media-breakpoint-only(lg) {
            //height: 900px;
            height: auto;
        }

        &.one {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 10px;
            font-size: 1.5em;
            text-align: center;
            b {
                font-weight: 600;
            }
            * {
                margin-bottom: 30px;
                @include media-breakpoint-down(md) {
                    margin-bottom: 0;
                }
            }

            @include media-breakpoint-down(md) {
                padding: 10px 0;
                height: 100%;
                background-color: rgba(219, 213, 217,1);
                border-radius: 0;
                p{
                        margin-bottom: 15px;
                }
                form{
                    margin-bottom: 10px;
                }
            }

            .btn-register {
                background-color: #f58a2d;
                color: white !important;
                font-size: 1.2em;
                min-width: 80%;
                @include media-breakpoint-down(lg) {
                    font-size: .8em;
                    width: 90%;
                }

            }

            input {
                padding: 5px 10px;
                width: 80%;
                font-size: 1em;
                border-radius: 5px;
                @include media-breakpoint-down(lg) {
                    font-size: .7em;
                    width: 90%;
                }
            }
        }
        &.two {
            text-align: center;
        }
    }
    .fixed-column{
        position: fixed;
        bottom: 0;
        padding: 0;
    }
    .mobile-form{
        display: flex;
        justify-content: space-around;
        width: 100%;
        .mobile-btn-register{
            background-color: #f58a2d;
            color: white !important;
            font-size: .8em !important;
            width: 40%;
        }
        .mobile-input{
            font-size: .8em !important;
            width: 50% !important;
        }
    }
    .main-content{
        @include media-breakpoint-down(md) {
            margin-bottom: 170px;
        }
    }
    hr.style-one {
        border: 0;
        height: 1px;
        background: #333;
        background-image: -webkit-linear-gradient(left, #ccc, #333, #ccc);
        background-image: -moz-linear-gradient(left, #ccc, #333, #ccc);
        background-image: -ms-linear-gradient(left, #ccc, #333, #ccc);
        background-image: -o-linear-gradient(left, #ccc, #333, #ccc);
    }
    .logo {
        width: 70%;
        @include media-breakpoint-down(md) {
            width: 60%;
        }
    }
</style>

