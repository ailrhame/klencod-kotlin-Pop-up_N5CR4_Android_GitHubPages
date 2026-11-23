# نشر Pop-up على GitHub Pages

1. أنشئ مستودعاً عاماً باسم `popup-pages` في حساب `airlhame`.
2. ارفع محتويات هذا المشروع إلى جذر المستودع، بما فيها مجلد `docs`.
3. افتح Settings → Pages.
4. اختر Deploy from a branch ثم `main` والمجلد `/docs` واضغط Save.
5. بعد اكتمال النشر يصبح الموقع: https://airlhame.github.io/popup-pages/

التطبيق ينشئ روابط من هذا الشكل:
`https://airlhame.github.io/popup-pages/?count=4&message=Hello&url=https%3A%2F%2Fexample.com`

الرسائل تظهر بالتتابع داخل صفحة الويب، ثم ينتقل المتصفح إلى الرابط المستهدف بعد ضغط زر المتابعة الأخير. لا يحتاج الزائر إلى تطبيق Android.

ملاحظة: المتصفحات تحظر النوافذ المنبثقة التلقائية غالباً؛ لذلك تستخدم الصفحة واجهة رسائل متتابعة بدلاً من فتح نوافذ مستقلة.
