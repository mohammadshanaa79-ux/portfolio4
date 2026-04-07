# 🚀 كيف تشغل المشروع على جهازك (localhost)

## 📋 المتطلبات
- Node.js مثبت على جهازك
- المشروع موجود على جهازك

---

## ⚡ خطوات التشغيل السريعة

### الخطوة 1️⃣: افتح CMD في مجلد المشروع
- افتح مجلد المشروع في File Explorer
- اضغط على شريط العنوان (Address Bar)
- اكتب `cmd` واضغط Enter

### الخطوة 2️⃣: ثبت المكتبات (أول مرة فقط)
```bash
npm install
```
⏳ انتظر 2-3 دقائق حتى تنتهي التثبيت

### الخطوة 3️⃣: جهز قاعدة البيانات (أول مرة فقط)
```bash
npx prisma generate
```
```bash
npx prisma db push
```
```bash
node prisma/seed.js
```

### الخطوة 4️⃣: شغل المشروع
```bash
npm run dev
```

### الخطوة 5️⃣: افتح المتصفح
افتح المتصفح واكتب:
```
http://localhost:3000
```

---

## 🎉 Perfect! The homepage opens with:
- ✅ Restaurant logo (URBAN BITES)
- ✅ Product menu (Burgers, Pizza, Chicken, Wraps, Drinks)
- ✅ Prices in dollars
- ✅ زر Dark Mode 🌙
- ✅ كل شي شغال!

---

## 🔄 في المرات الجاية (بعد ما تثبت كل شي)

فقط شغل:
```bash
npm run dev
```
وافتح: http://localhost:3000

---

## 🛑 لإيقاف المشروع
اضغط `Ctrl + C` في نافذة CMD

---

## 📄 الصفحات المتاحة

| الصفحة | الرابط |
|--------|--------|
| الرئيسية (المنتجات) | http://localhost:3000 |
| المنتجات | http://localhost:3000/products |
| العروض | http://localhost:3000/offers |
| من نحن | http://localhost:3000/about |
| تواصل معنا | http://localhost:3000/contact |
| تسجيل دخول | http://localhost:3000/login |
| لوحة الإدارة | http://localhost:3000/admin |

---

## 🔑 بيانات الدخول

### للإدارة (Admin):
- البريد: `admin@example.com`
- كلمة السر: `demo123`

### للعميل (Customer):
- البريد: `customer@test.ps`
- كلمة السر: `123456`

---

## ❓ مشاكل شائعة

### المشكلة: "npm not found"
**الحل:** ثبت Node.js من https://nodejs.org

### المشكلة: "Port 3000 already in use"
**الحل:** 
```bash
npx kill-port 3000
npm run dev
```

### المشكلة: الصفحة ما بتفتح
**الحل:**
1. تأكد إن CMD مفتوح ومكتوب فيه "Ready in..."
2. جرب: http://127.0.0.1:3000

---

## 🎯 ملاحظات مهمة

- ✅ المشروع بيشتغل على جهازك فقط (localhost)
- ✅ البيانات محفوظة في ملف `prisma/prisma/dev.db`
- ✅ لو بدك ترجع البيانات الأصلية: `node prisma/seed.js`
- ✅ لو بدك تشوف قاعدة البيانات: `npx prisma studio`

---

<div align="center">

**🍔 Enjoy URBAN BITES Restaurant! ✨**

</div>
