ازمایش شماره 1 روشن وخاموش شدن LED باکاراکتر:
   اول یک متغییر تعریف میکنیم که پایه ی 13 LED است وبعد ازان تابع voidsetupکه کدداخل قسمت خود را فقط یکباردراول اپلود اجرا میشود.دربخش تابع pinMode شماره پایه دیجیتال را می نویسیم و دربخش Mode که حالت پایه مشخض میکنیم و اگردرگاه ازنوع خروجی باشد از OUTPUT استفاده میکنیم داخل voidloop که کد را اجرا میکند و وقتی که تمام شد دوباره اون را ازاول اجرا میکنیم (loopبه معنای حلقه است Serial.begin تابع درزمینه ارتباط سریال است وبانرخ 9600 آغازمیکند و اگر SeriaL.availble اگرنعداد بایت های موجود بزرگتر ازصفر باشد وو دستور ()serial .read
   داده های سریال ورودی رامیخواند مقداریک متغییر را برابر با این تابع قرار دهیم تا داده های ورودی دران ذخیره شوند  واگر داده های ورودی مون برابر با H ,h باشد. تابع digitalWrite یک کنترل کننده ی دیجیتال است واین تابع دردوحالت به کارمیرود به صورت HIGH.LOW اگر به صورت HIGH باشددستورفعال سازی است ونشان از روشن شدن led دارد و led به  روشن می شود. و اگر داده های ورودی مون برابر با l, L باشد به صورت LOW باشد دستور توقف است و led خاموش میشود.

   ازمایش شماره 2 روشن و خاموش کردن LED با ON, OfF :
اول یک متغییر تعریف میکنیم که پایه ی 9 LED است وبعد ازان تابع voidsetupکه کدداخل قسمت خود را فقط یکباردراول اپلود اجرا میشود.دربخش تابع pinMode شماره پایه دیجیتال را می نویسیم و دربخش Mode که حالت پایه مشخض میکنیم و اگردرگاه ازنوع خروجی باشد از OUTPUT استفاده میکنیم داخل voidloop که کد را اجرا میکند و وقتی که تمام شد دوباره اون را ازاول اجرا میکنیم (loopبه معنای حلقه است Serial.begin تابع درزمینه ارتباط سریال است وبانرخ 9600 آغازمیکند و اگر SeriaL.availble اگرنعداد بایت های موجود بزرگتر ازصفر باشد ودستورهای رشته های سریال ورودی را میخواند رامیخواند مقداریک متغییر را برابر با این تابع قرار دهیم تا داده های ورودی دران ذخیره شوند  واگر داده های ورودی مون برابر با ONباشد. تابع digitalWrite یک کنترل کننده ی دیجیتال است واین تابع دردوحالت به کارمیرود به صورت HIGH.LOW اگر به صورت HIGH باشددستورفعال سازی است ونشان از روشن شدن led دارد و led روشن می شود. و اگر داده های ورودی مون برابر با OFFباشد به صورت LOW باشد دستور توقف است و led خاموش میشود.
   
   ازمایش شماره3 خاموش وروشن کردن LED:
   اول دوتامتغییر تعریف میکنیم پایه 13و 9 LED است. همه voidsetup که کد داخل قسمت خود را فقط یکبار آپلود میکند.دربخش تابع pinMode شماره پایه دیجیتال را می نویسیم و دربخش Mode حالت پایه مشخض میشود. مرحله ی بعد داخل voidloop که کد را اجرا میکند و وقتی که تمام شد دوباره اون را ازاول اجرا میکنیم (loopبه معنای حلقه است). تابع digitalWrite یک کنترل کننده ی دیجیتال است واین تابع دردوحالت به کارمیرود به صورت HIGH.LOW اگر به صورت HIGH باشددستورفعال سازی است ونشان از روشن شدن led دارد و led به مدت 5ثانیه روشن می باشد و اگر به صورت LOW باشد دستور توقف است و led خاموش میشود. وتابع delay اجرای دستورات بعدی رو به مدت زمان دلخواه متوقف می کند پس ازپایان ادامه روند برنامه است و دراین برنامه دستور توقف برنامه به مدت 500ثانیه می باشد.
   
