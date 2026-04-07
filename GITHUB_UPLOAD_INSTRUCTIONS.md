# 📤 تعليمات رفع المشروع على GitHub

## ✅ تم حفظ جميع التغييرات بنجاح!

تم حفظ 72 ملف معدل في commit واحد.

---

## 🚀 خطوات رفع المشروع على GitHub:

### الخطوة 1️⃣: إنشاء مستودع جديد على GitHub

1. اذهب إلى: https://github.com/new
2. املأ المعلومات:
   - **Repository name**: `urban-bites-restaurant`
   - **Description**: `🍔 URBAN BITES Restaurant - Fresh Food, Urban Vibes ✨`
   - اختر: **Public** أو **Private** (حسب رغبتك)
   - ❌ **لا تختر** "Add a README file"
   - ❌ **لا تختر** "Add .gitignore"
   - ❌ **لا تختر** "Choose a license"
3. اضغط **Create repository**

---

### الخطوة 2️⃣: ربط المشروع بـ GitHub

افتح Terminal في مجلد المشروع وقم بتنفيذ الأوامر التالية:

```bash
# ربط المشروع بـ GitHub (غير YOUR_USERNAME باسم حسابك)
git remote add origin https://github.com/YOUR_USERNAME/urban-bites-restaurant.git

# تغيير اسم الفرع إلى main
git branch -M main

# رفع الملفات إلى GitHub
git push -u origin main
```

---

### الخطوة 3️⃣: إدخال بيانات الدخول

عند تنفيذ أمر `git push`، سيطلب منك:
- **Username**: اسم المستخدم في GitHub
- **Password**: استخدم **Personal Access Token** (ليس كلمة المرور العادية)

#### كيفية إنشاء Personal Access Token:
1. اذهب إلى: https://github.com/settings/tokens
2. اضغط **Generate new token** → **Generate new token (classic)**
3. أعطه اسم مثل: `urban-bites-upload`
4. اختر Expiration: **90 days** أو **No expiration**
5. اختر Scopes: ✅ **repo** (كل الصلاحيات)
6. اضغط **Generate token**
7. **انسخ التوكن فوراً** (لن تراه مرة أخرى!)
8. استخدمه بدلاً من كلمة المرور

---

## 📋 معلومات المشروع المحفوظة:

### 🏪 معلومات المطعم:
- **الاسم**: URBAN BITES
- **الشعار**: Fresh Food, Urban Vibes
- **الهاتف**: +970 599 123 456
- **البريد**: info@urbanbites.com
- **العنوان**: Ramallah, Palestine

### 👤 حسابات الدخول:
- **Admin**: admin@example.com / demo123
- **Customer**: customer@example.com / demo123

### 🎨 التصميم:
- اللون الذهبي: #eab308
- خلفية سوداء مع جزيئات ذهبية متحركة (20 جزيء)
- تصميم عصري مع تأثيرات Glass

### 📦 الملفات المحفوظة:
- 72 ملف تم حفظها
- Commit message: "Update restaurant branding: Changed from SHIK SHAK to URBAN BITES with new contact info and golden theme"

---

## 🔄 للتحديثات المستقبلية:

عند إجراء تعديلات جديدة، استخدم:

```bash
# إضافة الملفات المعدلة
git add .

# حفظ التغييرات
git commit -m "وصف التغييرات هنا"

# رفع التغييرات
git push
```

---

## ✨ نصائح إضافية:

1. **ملف .env**: لا يتم رفعه على GitHub (محمي بـ .gitignore)
2. **قاعدة البيانات**: ملف dev.db لا يتم رفعه
3. **node_modules**: لا يتم رفعه (سيتم تثبيته عند الاستنساخ)

---

## 🌐 بعد الرفع:

يمكنك نشر المشروع على:
- **Vercel**: https://vercel.com (مجاني ومثالي لـ Next.js)
- **Netlify**: https://netlify.com
- **Railway**: https://railway.app

---

**🎉 جاهز للرفع! حظاً موفقاً!**
