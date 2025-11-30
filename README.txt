راهنما — Deploy روی GitHub Pages

1) یک مخزن جدید در GitHub بساز (مثلاً online-pardis-9-2)
2) همه فایل‌های این پوشه را آپلود کن (index.html, styles.css, teacher-login.html, student-login.html, teacher-dashboard.html, classroom.html, README.txt)
3) در صفحه ریپو: Settings -> Pages -> Branch = main (یا branch که آپلود کردی) -> folder = / (root) -> Save
4) بعد از چند ثانیه آدرس سایت فعال می‌شود (https://yourusername.github.io/online-pardis-9-2/)

نکات مهم:
- رمز پیش‌فرض معلم: pardis-teacher-2025 (در فایل teacher-login.html قابل تغییر است)
- همهٔ داده‌ها (لیست دانش‌آموز، فایل‌ها، حضور و غیاب، تکالیف) در LocalStorage مرورگر ذخیره می‌شوند.
- اگر بخواهی همه چیز را آنلاین و همگام‌سازی‌شده داشته باشی (تا معلم‌ها و مدیر مدرسه از هر دستگاه ببینند)، باید پس از این مرحله یک backend اضافه شود (مثلاً Firebase). من می‌تونم در مرحلهٔ بعدی این را برایت انجام دهم.
- محدودیت حجم فایل‌ها: LocalStorage برای فایل‌های بزرگ مناسب نیست؛ برای فایل‌های سنگین بهتر است از Google Drive یا اضافه کردن فضای سروری استفاده شود.
