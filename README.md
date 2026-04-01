# My Order

My Order هو مشروع واجهة أمامية احترافية لطلب الطعام تم تطويره باستخدام HTML وCSS وJavaScript.

## ما تم تحسينه

- إعدادات SEO وOpen Graph أفضل.
- دعم PWA عبر `manifest.json`.
- إعدادات مسار نسبي (`./`) لتعمل بشكل صحيح على GitHub Pages.
- تصميم ومحتوى جاهز للنشر على الإنترنت.

## النشر على GitHub Pages

1. أنشئ مستودع جديد على GitHub.
2. ارفع ملفات المشروع إلى المستودع.
3. في إعدادات المستودع، اذهب إلى `Pages` ثم اختر فرع `main` أو `master` والمجلد `/(root)`.
4. احفظ الإعدادات.
5. سيكون رابط الموقع:

   `https://<your-github-username>.github.io/<your-repo>/`

### مثال

إذا كان اسم المستخدم `ibrahim123` واسم المستودع `My-Order`، يكون الرابط:

`https://ibrahim123.github.io/My-Order/`

## ملاحظة

- إذا أردت رابطًا دائمًا أكثر احترافية، عدّل قيمة `og:url` و `canonical` في `index.html` إلى رابط GitHub Pages النهائي.
- إذا استخدمت فرع `gh-pages` بدلاً من `main`، اختر هذا الفرع في إعدادات GitHub Pages.

## ملفات مهمة

- `index.html` — الصفحة الرئيسية.
- `style.css` — تصميم الواجهة.
- `script.js` — وظائف طلب الطعام وجلب البيانات.
- `manifest.json` — إعداد تطبيق الويب التقدمي.
- `.nojekyll` — يمنع GitHub Pages من تجاهل الملفات أو المجلدات التي تبدأ بشرطة سفلية.
