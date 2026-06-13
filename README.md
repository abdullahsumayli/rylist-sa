# RYLIST GLOBAL — الموقع التعريفي (rylist.sa)

موقع تعريفي ثابت (HTML/CSS فقط) لشركة **RYLIST GLOBAL**. مشروع مستقل تماماً عن كود صامل — يُنشر لوحده على دومين `rylist.sa`.

## الملفات

| الملف | الصفحة |
|------|--------|
| `index.html` | الرئيسية |
| `about.html` | من نحن |
| `services.html` | خدماتنا |
| `products.html` | منتجاتنا |
| `why.html` | لماذا RYLIST |
| `contact.html` | تواصل |
| `styles.css` | التنسيق المشترك لكل الصفحات |

كل الصفحات تربط `styles.css`. اللوجو والفافيكون **مدمجان داخل الصفحات** (مو ملفات خارجية)، والخطوط من Google Fonts (تحتاج إنترنت عند الفتح).

## النشر على Vercel

1. ارفع هذا المجلد كمشروع جديد في Vercel (Framework Preset: **Other** — موقع ثابت، بدون build).
2. بعد النشر، أضف الدومين `rylist.sa` في إعدادات المشروع (Domains).
3. صفحة البداية تلقائياً `index.html`.

> صامل منتج منفصل على `samail.rylist.sa` بمشروعه الخاص — لا تخلط الاثنين.

## معلّق (قبل الإطلاق)

- **نموذج التواصل** في `contact.html` يفتح بريد (mailto). للاستقبال الفعلي اربطه بخدمة نماذج (Formspree / Web3Forms).
- أكّد أن **`info@rylist.sa`** صندوق بريد شغّال.
- (اختياري) صورة OG رسمية، وملف `sitemap.xml`.

—
© 2026 RYLIST GLOBAL
