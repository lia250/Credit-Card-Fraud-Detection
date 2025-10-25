# <p dir="rtl" align="justify">سیستم تشخیص کلاهبرداری کارت اعتباری با الگوریتم Naive Bayes</p>

### <p dir="rtl" align="justify">معرفی پروژه:</p>
<p dir="rtl" align="justify">این پروژه یک سیستم تشخیص کلاهبرداری کارت اعتباری با استفاده از الگوریتم Naive Bayes پیاده‌سازی کرده است. هدف اصلی شناسایی تراکنش‌های متقلبانه با دقت بالا است.</p>

### <p dir="rtl" align="justify">اهداف پروژه:</p>
<ul dir="rtl" align="justify">
   <li> ساخت مدل یادگیری ماشین برای تشخیص کلاهبرداری</li>
   <li> مدیریت عدم تعادل کلاس‌ها در دیتاست</li>
   <li> ارزیابی عملکرد مدل با معیارهای مختلف</li>
   <li> ارائه راهکارهای بهبود مدل</li>
</ul>

### <p dir="rtl" align="justify">مشخصات دیتاست:</p>
<ul dir="rtl" align="justify">
   <li>منبع: Kaggle Credit Card Fraud Detection</li>
   <li>تعداد نمونه: 284,807 تراکنش</li>
   <li>تعداد ویژگی‌ها: 31 ویژگی</li>
   <li>تراکنش‌های عادی: 284,315 (99.83%)</li>
   <li>تراکنش‌های متقلبانه: 492 (0.17%)</li>
</ul>

### <p dir="rtl" align="justify">ویژگی‌های دیتاست:</p>
<ul dir="rtl" align="justify">
   <li>ویژگی‌های V1 تا V28: نتایج تحلیل PCA (محافظت‌شده)</li>
   <li>Time: زمان تراکنش</li>
   <li>Amount: مبلغ تراکنش</li>
   <li>Class: برچسب (0=عادی, 1=متقلبانه)</li>
</ul>

### <p dir="rtl" align="justify">توزیع کلاس‌ها:</p>
<p dir="rtl" align="justify">دیتaset دارای عدم تعادل شدید است:</p>
<ul dir="rtl" align="justify">
   <li>تراکنش‌های عادی: 99.83%</li>
   <li>تراکنش‌های متقلبانه: 0.17%</li>
</ul>
