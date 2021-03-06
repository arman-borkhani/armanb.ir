---
layout: post
author: آرمان بورخانی
title: استفاده از سرویس های image placeholder در پروژه های طراحی قالب
---

تو اکثر پروژه ها از تصاویر استفاده میشه ، زمانی که دارید روی نسخه اولیه یا پیش نمایش یه قالب کار می کنید لازم دارید تصاویر با ابعاد مختلف را روی قالب امتحان کنید. برش دادن تصاویر با نرم افزار های مختلف برای بدست آوردن اندازه مناسب می تونه کار زمان بر و سختی باشه.با استفاده از سرویس های image placeholder می تونید بطور رایگان تصاویری با ابعاد دلخواهتون را در صفحه پروژه بارگذاری کنید. معمولا شما با قرار دادن یک url در خاصیت(Attribute) سورس(src) تگ img می تونید تصویر را در قالب نمایش بدید.

## [placeholder.com](https://placeholder.com/)

![سرویس های image placeholder](/assets/images/Placeholder-com-Quick-Simple-Placeholder-Images.png){:.full-width}

برای اینکه بتونید از تصاویر این وبسایت استفاده کنید باید خاصیت سورس تگ img را شبیه کد زیر مقدار دهی کنید.

~~~markup
<img src="http://via.placeholder.com/350x150">
~~~

با این کار یه تصویر با طول 350 و عرض 150 در صفحه نمایش داده میشه. شما به راحتی می تونید با تغییر دو عدد بعد از آدرس سایت اندازه تصویر را تغییر بدید.

## [placehold.co](https://placehold.co/)

این سرویس هم شبیه سرویس قبلی با این تفاوت که شما می تونید رنگ پس زمینه و رنگ متن را تغییر بدید و یا متنی دلخواه را با اعداد روی تصویر جایگزین کنید.

بصورت پیش فرض شما باید تگ img را به شکل زیر وارد پروژه کنید.

~~~markup
<img src="https://placehold.co/600x400">
~~~

برای تعیین رنگ باید ابتدا رنگ پس زمینه و سپس رنگ متن را بصورت زیر مشخص کنید

~~~markup
<img src="https://placehold.co/600x400/orange/white">
~~~
برای نمایش متن دلخواه روی تصویر بصورت زیر عمل کنید. علامت + نمایانگر فاصله است

~~~markup
<img src="https://placehold.co/600x400?text=Hello+World">
~~~

## [picsum.photos](http://picsum.photos/)

![سرویس های image placeholder](/assets/images/Lorem-Picsum.png){:.full-width}


سرویس های قبلی یه تصویر ثابت برای شما نمایش می دهند. اما این سرویس یک تصویر از وبسایت unsplash که منبعی از تصاویر رایگانه برای شما بارگذاری می کنه.برای استفاده از این سرویس باید تگ img را بصورت زیر وارد سندتون کنید.

~~~markup
<img src="https://picsum.photos/200/300">
~~~
اگر به انتهای url بالا مقدار random? را اضافه کنید با هر بار رفرش کردن صفحه، تصویر جدیدی با همون ابعاد جایگزین تصویر قبلی میشه.

~~~markup
<img src="https://picsum.photos/200/300/?random">
~~~

اگه بخواهید چندتا تصویر به صفحه اضافه کنید بطوری که شبیه هم نباشن باید به هر تصویر یک شماره که id تصویر بشمار میاد اختصاص بدید؛ لیست تصاویر را می تونید در [ایـــــــــن](https://picsum.photos/images) آدرس ببینید.

~~~markup
<img src="https://picsum.photos/200/300?image=0">
~~~

همچنین مشخصات دیگری هم می تونید به تصاویر اضافه کنید مانند انتخاب تصاویر سیاه و سفید با اضافه کردن g/ بعد از آدرس سایت.

~~~markup
<img src="https://picsum.photos/g/200/300">
~~~

## [placeimg.com](http://placeimg.com/)

با استفاده از کد زیر شما می تونید از این سرویس استفاده کنید. با هر بار رفرش کردن صفحه تصویر جدیدی جایگزین قبلی میشه.

~~~markup
<img src="https://placeimg.com/640/480/any">
~~~

درضمن شما می تونید با وارد کردن اندازه های دلخواه و انتخاب کردن یکی از دسته های حیوانات ، معماری ، طبیعت ، جمعیت و تکنولوژی تصویری دانلود کنید و ازش استفاده کنید.

سرویس های زیادی از این دست وجود دارند، برای پیدا کردن موارد دیگر عبارت image placeholder را جستجو کنید.