---
layout: post
author: آرمان بورخانی
title: غیرفعال کردن افزونه در یک صفحه خاص از وردپرس 
---
گاهی وقتا بعد از نصب یک افزونه (Plugin) وردپرسی برخی از صفحات وردپرس دچار بهم ریختگی  میشن. دلیل این اتفاق میتونه تداخل (conflict) بین کد های جی کوئری وردپرس و افزونه نصب شده باشه. یکی از راه حل های این مشکل که برای من کارساز بود اینه که افزونه مورد نظر را در صفحه ای که دچار مشکل شده غیرفعال کنید؛ ساده ترین راه برای غیرفعال کردن افزونه در یک صفحه یا برگه ، استفاده از افزونه Plugin Organizer هست.

شما می تونید در ادامه نحوه انجام این کار را یاد بگیرید.

همینطور که واضحه ابتدا افزونه Plugin organizer را نصب کنید.
![غیرفعال کردن افزونه](/assets/images/1.png){:.full-width}

در منوی سمت راست گزینه plugin organizer را انتخاب کنید تا وارد تنظیمات این افزونه شوید. برای اینکه بتونید افزونه ای را در یک صفحه خاص غیرفعال کنید باید قابلیت Selective Plugin Loading را فعال کنید. برای این کار روی باتن off  کلیک کنید تا قابلیت مورد نظر فعال( on) بشه.

![افزونه plugin organizer](/assets/images/2.png){:.full-width}

اگر ماوس را روی علامت سوال ببرید توضیحی ظاهر میشه با این عنوان : فایل pluginOrganizerMu.class.php را از مسیر wp-content/plugin_organizer/lib کپی کنید و در پوشه mu-plugins  که در همان پوشه wp-content قرار داره کپی کنید و اگر پوشه mu-plugins وجود نداشت اون را بسازید و بعد کپی کنید.

 
حالا از منو سمت راست گزینه (منوی اصلی داخل پیشخوان) “برگه ها” را انتخاب کنید. در صفحه باز شده شما همه ی صفحات یا برگه های وبسایت را می بینید. صفحه ای که قرار است افزونه را در آن غیرفعال کنید انتخاب کنید. در پایین صفحه در قسمت Available Items همه ی افزونه هایی که در صفحه مورد نظر فعال هستند لیست شده اند.


برای غیرفعال کردن پلاگین باید اونو از جدول سمت چپ یعنی آیتم های فعال با استفاده از ماوس بکشید (Drag) و در جداول سمت راست رها (Drop) کنید.

![افزونه plugin organizer](/assets/images/3-1.png){:.full-width}

در آخر به روز رسانی را بزنید تا تغییرات در برگه ذخیره بشه.

می تونید افزونه را در [ایــــــــــن](https://wordpress.org/plugins/plugin-organizer/) آدرس ببینید.