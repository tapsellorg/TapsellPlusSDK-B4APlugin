

<div dir='rtl'>

**English README**? [Here](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/blob/main/README-EN.md)

# پلاگین B4a تپسل‌پلاس

## مشکل یا سوال

مستندات کامل تپسل پلاس از 
[این لینک](https://docs.tapsell.ir/plus-sdk/b4a/main/)
قابل دسترسی هستند. برای استفاده از تپسل پلاس حتما این مستندات مطالعه شوند


لیست سوالات قبلا پرسیده شده از [این لینک](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues?q=is%3Aissue) قابل مشاهده است. در صورتی که سوال شما وجود نداشت آنرا از [این لینک](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues/new) بپرسید

## راه‌اندازی

> **نکته‌ی مهم**:‌ نسخه‌ی B4A پیشنهادی **۱۱** می‌باشد.

ابتدا از صفحه‌ی دانلود پلاگین مورد نظر را دانلود کنید.


[**صفحه‌ی دانلودها**](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/releases)

سپس:  
- آنرا اکسترکت کنید
- فایل‌های `TapsellPlusB4A.jar` و `TapsellPlusB4A.xml` را در Libraries قرار دهید
- فایلهای درون پوشه‌ی `libs` را درون **additional libraries** قرار دهید
- **نکته**: همچنین میتوانید فایل Jar و XML قدم دوم را نیز در Additional libraries قرار دهید.
- در پروژه‌ی خود پس از Refresh کردن لایبرری‌ها تیک این لایبرری‌ها را بزنید:
  - TapsellPlusB4A
  - OKHttp

حال به بخش استفاده مراجعه کنید


### نکات راه اندازی
- از ریسورس‌های پیشنهادی B4A (SDK و کتابخانه‌ها) استفاده کنید. [لینک](https://www.b4x.com/b4a.html)


## استفاده
ابتدا بایستی SDK را **Initialize** کنید:

کد زیر را در `Sub Globals` قرار دهید:

</div>

```vb
Dim tapsellPlus As TapsellPlus
Dim tapsellPlusAppId As String = "شناسه‌ی تپسل پلاس شما"
```

<div dir='rtl'>

**نکته‌ي مهم**: شناسه‌ی تپسل پلاس خود را پس از ساخت اپلیکیشن در داشبورد تپسل بدست آورده و قرار دهید

[**اطلاعات بیشتر در مورد تپسل پلاس**](https://tapsell.ir/tapsellplus/)

سپس از کد زیر برای Initialize استفاده کنید.

این کد را در بخش `Activity_Create` قرار دهید:


</div>


```vb
tapsellPlus.Initialize(tapsellPlusAppId)
```

<div dir='rtl'>

برای نمایش تبلیغ و مستندات کامل‌تر بخش "مستندات کامل" را مطالعه نمایید


## مستدات کامل


مستندات کامل تپسل پلاس از 
[این لینک](https://docs.tapsell.ir/plus-sdk/b4a/main/)
قابل دسترسی هستند. برای استفاده از تپسل پلاس حتما این مستندات مطالعه شوند

**در صورت وجود مشکل یا سوال** لیست سوالات قبلا پرسیده شده از [این لینک](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues?q=is%3Aissue) قابل مشاهده است. در صورتی که سوال شما وجود نداشت آنرا از [این لینک](https://github.com/tapsellorg/TapsellPlusSDK-B4APlugin/issues/new) بپرسید

</div>