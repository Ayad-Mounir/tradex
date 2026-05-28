# TradeX — منصة التداول الذكية

PWA لتحليل وتنفيذ الصفقات على حسابات التداول الشخصية.

## المراحل

| # | المرحلة | الحالة |
|---|---------|--------|
| 1 | Auth + PWA Shell | ✅ مكتملة |
| 2 | ربط حساب التداول | ⏳ قادمة |
| 3 | Dashboard + صفقات | ⏳ قادمة |
| 4 | الاستراتيجيات | ⏳ قادمة |
| 5 | Admin Panel | ⏳ قادمة |

## الإعداد

1. أنشئ مشروع Firebase على [firebase.google.com](https://firebase.google.com)
2. فعّل **Authentication → Google**
3. أنشئ **Firestore Database**
4. انسخ إعدادات المشروع داخل `index.html` في متغير `firebaseConfig`
5. أضف دومين GitHub Pages في Firebase → Authentication → Authorized domains

## التقنيات

- Firebase Auth (Google Sign-In)
- Cloud Firestore (قاعدة البيانات)
- PWA (Service Worker + Manifest)
- HTML/CSS/JS خالص — بدون frameworks
