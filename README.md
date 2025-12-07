# نظام متابعات المخالفات السكنية الجامعية

هذه نسخة جاهزة لنشر على GitHub Pages. الملف الرئيسي هو `index.html`.

## ملاحظات سريعة
- اسم المشرف الافتراضي: `المشرف الرئيسي`
- كلمة المرور الافتراضية للمشرف الرئيسي: `admin123`
- البيانات (المخالفات، المستخدمون) مخزنة محليًا في `localStorage` بالمتصفح.

## خطوات سريعة لنشر الموقع على GitHub (الأوامر)
1. أنشئ مستودعًا جديدًا على GitHub (مثلاً: `tabee-site`).
2. في جهازك نفّذ:
```bash
git init
git add .
git commit -m "Initial commit - Tabee site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```
3. في إعدادات المستودع على GitHub > Pages: اختر الفرع `main` والمجلد `/ (root)` ثم اضغط حفظ. بعد دقائق سيظهر رابط الموقع ضمن GitHub Pages.

بدائل:
- يمكنك رفع الملفات مباشرة عبر واجهة الويب (Upload files) ثم ضبط GitHub Pages.
- لإنشاء نطاق مخصص، أضف ملف `CNAME` يحتوي على اسم النطاق داخل المستودع.

## ملفات داخل الحزمة
- `index.html` — ملف الموقع (مُعاد التسمية من `tabee.html`)
- `README.md` — هذه التعليمات
- `.nojekyll` — لتجنب معالجة Jekyll على GitHub Pages

إذا رغبت، أستطيع:
- تجهيز ملف `CNAME` أو إعداد ملف `LICENSE` (MIT).
- إنشاء فرع `gh-pages` وملفات إعداد GitHub Actions (إذا أردت نشر تلقائي من الفرع `main`).
- أو أرفع المستودع نيابةً عنك إذا أعطيتني صلاحية وصول (لا تشارك بيانات سرية هنا).
