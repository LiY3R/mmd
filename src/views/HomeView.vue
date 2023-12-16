<script setup>
</script>
<template>
    <main>
            <div class="top">
                <div class="imgdiv">
                    <img src="../assets/iphone.jpg" alt="iphone" class="pic">
                </div>
                <div class="vs">
                   vs
                </div>
                <div class="imgdiv">
                    <img src="../assets/samsung.jpg" alt="samsung" class="pic">
                </div>
            </div>
        <div id="bigtext">
            <div>
                <p class="h"> مقایسه Iphone 15 و S23  </p>
            </div>
            <div>
                <p class="tx1">آیفون 15 پرو مکس و گلکسی S23 اولترا شباهت‌های زیادی دارند و هر 
                    دو، بهترین گوشی‌های پرچمدار ساخته شده توسط شرکت خودشان هستند. در ادامه،
                     تفاوت‌های اصلی آیفون 15 پرو مکس و گلکسی اس 23 اولترا را مشاهده می‌کنید:</p>
            </div>
            <div class="uls">
                <ul>
                    <li>نمایشگر ۶.۷ اینچی (آیفون ۱۵ پرو مکس) و نمایشگر ۶.۸ اینچی (گلکسی اس ۲۳ اولترا)</li>
                    <li>پردازنده 3 نانومتری اپل A17 پرو (آیفون 15 پرو مکس) و پردازنده 4 نانومتری کوالکام اسنپدراگون 8 نسل 2 (گلکسی اس 23 اولترا)</li>
                    <li>دوربین اصلی ۴۸ مگاپیکسلی (آیفون ۱۵ پرو مکس) و دوربین اصلی ۲۰۰ مگاپیکسلی (گلکسی اس ۲۳ اولترا)</li>
                    <li>زوم اپتیکال ۵ برابری (آیفون ۱۵ پرو مکس) و زوم اپتیکال ۳ و ۱۰ برابری (گلکسی اس ۲۳ اولترا)</li>
                    <li>پشتیبانی از قلم S Pen (گلکسی اس 23 اولترا)</li>
                    <li>باتری ۴۴۴۱ میلی‌آمپر ساعتی (آیفون ۱۵ پرو مکس) و باتری ۵۰۰۰ میلی‌آمپر ساعتی (گلکسی اس ۲۳ اولترا)</li>
                    <li>سرعت شارژ ۲۵ وات (آیفون ۱۵ پرو مکس) و ۴۵ وات (گلکسی اس ۲۳ اولترا)</li>
                    <li>فیس آی‌دی (آیفون ۱۵ پرو مکس) و حسگر اثرانگشت درون نمایشگر (گلکسی اس ۲۳ اولترا)</li>
                </ul>
            </div>
        </div>
        <hr/>
        <div class="divpic2">
            <img src="../assets/Capture.PNG" alt="capture" class="pic2">
        </div>
        <hr/>
        <div id="poco">
            <div class="tx3">
                <p class="h">
                    گوشی موبایل شیائومی POCO X5 pro ظرفیت 256 رم 8 گیگابایت
                </p>
                <p class="tx3p1">ویژگی های محصول</p>
                <ul>
                        <li><span class="tx3p3">ابعاد: <span class="tx3p2"> 7.9*76*162.9 میلیمتر</span></span></li>
                        <li><span class="tx3p3">سیستم عامل: <span class="tx3p2">Android 12</span></span></li>
                        <li><span class="tx3p3">تراشه: <span class="tx3p2">Qualcomm SM7325 Snapdragon 778G 5G (6 nm)</span></span></li>
                        <li><span class="tx3p3">حافظه داخلی: <span class="tx3p2"> 256 گیگابایت</span></span></li>
                        <li><span class="tx3p3">RAM مقدار : <span class="tx3p2">8 گیگابایت</span></span></li>
                        <li> <span class="tx3p3">فناوری صفحه‌نمایش: <span class="tx3p2"> AMOLED</span></span></li>
                        <li><span class="tx3p3">اندازه صفحه نمایش: <span class="tx3p2"> 6.67 اینچ</span></span></li>
                </ul>
            </div>
            <div class="pic3">
                <img src="../assets/poco.jpg" alt="poco x5" class="imgpoco">
            </div>
        </div>
        <hr/>
    </main>
</template>
<style scoped>
    main{
        width: 100%;
        height: 1700px;
        background-color: white;
        direction: rtl;
    }
    .top {
        width: 1288px;
        height: 400px;
        display: flex;
        box-shadow: 0rem 1px 20px 2px;
        margin-top: 10px;
    }
    .imgdiv {
        width: 600px;
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: center;
        }
    .vs {
        width: 89px;
        height: 400px;
        font-size: 50px;
        display: flex;
        align-items: center;
        }
    .pic {
        width: 300px;
    }
    .h {
        font-size: 28PX;
        margin-right: 20px;
        font-weight: 600;
    }
    .tx1 {
        font-size: 20px;
        margin-right: 20px;
        color: #383535;
        line-height: 1.7;   
    }
    .uls {
        font-size: 20px;
        line-height: 1.7;
        color: #383535;
    }
    .divpic2 {
        width: 1300px;
        height: 330px;
        display: flex;
        justify-content: center;
    }
    .pic2 {
        width: 900px;
    }
    #poco {
        width: 1300px;
        height: 400px;
        display: flex;
        box-shadow: 0rem 1px 20px 2px;
    }
    .pic3 {
        width: 650px;
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .imgpoco {
        width: 400px;
    }
    .tx3 {
        width: 650px;
        height: 400px;
    }
    .tx3p1 {
        font-size: 20px;
        margin-right: 22px;
        font-weight: 600;
    }
    .tx3p2 {
        color: #a4a4a4; 
    }
    .tx3p3 {
        color: black;
    }
    li {
        color: red;
    }
</style>