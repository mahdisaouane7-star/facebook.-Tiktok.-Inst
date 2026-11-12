# MAHDI SAOUANE — Mes liens / روابطي

صفحة روابط شخصية (Link-in-Bio) بتصميم أنيق بلمسة ذهبية، تعمل بملف HTML واحد فقط بدون أي تبعيات أو خطوات بناء.

A single-file, dependency-free "link in bio" landing page with an elegant gold-on-cream design.

---

## المحتوى / What's inside

| الملف / File | الوصف / Description |
|---|---|
| `index.html` | الصفحة كاملة (HTML + CSS مدمج) — الصفحة الرئيسية الجاهزة للنشر / The complete page (inline CSS), ready to publish |
| `README.md` | هذا الملف / This file |

### المميزات / Features

- **ملف واحد** — لا حاجة إلى npm أو build / Single file, no build step.
- **الوضع الليلي تلقائيًا** عبر `prefers-color-scheme` / Automatic dark mode.
- **متجاوب** مع الهواتف (عرض أقصى 440px) / Mobile-first, max width 440px.
- **خطوط Google Fonts**: Cormorant Garamond، Inter، Amiri.
- **روابط**: Facebook، Instagram، TikTok، WhatsApp، Gmail.

### الروابط المضمّنة / Included links

- Facebook — https://www.facebook.com/share/1FKGxKkBwY/
- Instagram — https://www.instagram.com/saouanemahdi
- TikTok — https://www.tiktok.com/@mahdi.saouane
- WhatsApp — https://wa.me/qr/BBFSKTZKOGN3O1

لتغيير أي رابط، افتح `index.html` وابحث عن `href=` ثم عدّل القيمة.

To change a link, open `index.html`, search for `href=`, and replace the value.

---

## النشر عبر GitHub Pages / Publish with GitHub Pages

1. أنشئ مستودعًا جديدًا (Public) مثلًا باسم `links`.
2. ارفع `index.html` و `README.md` عبر **Add file → Upload files** ثم **Commit**.
3. من **Settings → Pages**: اختر Branch = `main` والمجلد = `/ (root)` ثم **Save**.
4. بعد دقيقة سيصبح رابطك: `https://<username>.github.io/links/`

> ملاحظة: على GitHub Pages يجب أن يكون الملف باسم `index.html` في جذر المستودع — وهو الحال هنا.
> Note: GitHub Pages requires the entry file to be named `index.html` at the repo root — already done.

### معاينة محليًا / Preview locally

```bash
python3 -m http.server 8000
# ثم افتح http://localhost:8000
```

---

© MAHDI SAOUANE
