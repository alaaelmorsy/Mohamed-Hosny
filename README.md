# منصة الاختبارات — قناة الإصدارات الرسمية

هذا المستودع مخصص لنشر إصدارات برنامج منصة الاختبارات (exe) فقط.

- لا يحتوي على أي كود مصدري.
- أحدث إصدار: انظر صفحة [Releases](https://github.com/alaaelmorsy/Mohamed-Hosny/releases/latest).

## التشغيل
1. حمّل `exam-platform.exe` و `.env.example` من آخر إصدار.
2. انسخ `.env.example` إلى `.env` بجانب الـ exe وعدّل بيانات MySQL.
3. `exam-platform.exe migrate` مرة واحدة لإنشاء القاعدة والجداول.
4. `exam-platform.exe` لتشغيل الخادم، ثم افتح `http://localhost:3000/admin`.
