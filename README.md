# 🍔 URBAN BITES Restaurant 🍕

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Online Food Ordering Platform for URBAN BITES Restaurant**

**Fresh Food, Urban Vibes** ✨

[التجربة المباشرة](#-التشغيل-السريع) • [المميزات](#-المميزات-الرئيسية) • [التقنيات](#️-التقنيات) • [دليل GitHub](GITHUB_GUIDE.md)

</div>

---

## 🌟 المميزات الجديدة

- 🌙 **Dark Mode** - وضع ليلي مريح للعين
- ✨ **Animations** - حركات سلسة وجذابة
- 🎨 **UI/UX محسّن** - تصميم عصري وسهل الاستخدام
- ⚡ **Performance** - تحسينات في الأداء والسرعة
- 📱 **Responsive** - متجاوب 100% مع جميع الأجهزة

## 📸 لقطات الشاشة

<div align="center">
  <h2>🍔 URBAN BITES Restaurant</h2>
</div>

## 🚀 نظرة سريعة

موقع ويب متكامل لطلب الطعام مع لوحة تحكم إدارية. مبني بأحدث التقنيات لتوفير تجربة مستخدم سلسة وسريعة.

## ✨ المميزات الرئيسية

### للعملاء 👥
- 🛒 تصفح المنتجات حسب التصنيفات
- 🔍 بحث وفلترة متقدمة
- 🛍️ سلة تسوق تفاعلية
- 📦 تتبع الطلبات
- 💳 نظام Checkout سهل
- 🎁 عرض العروض والخصومات
- 📱 تصميم متجاوب بالكامل
- 🌙 وضع ليلي (Dark Mode)

### للإدارة 👨‍💼
- 📊 لوحة تحكم شاملة مع إحصائيات
- 📦 إدارة المنتجات والتصنيفات
- 📋 إدارة الطلبات وتتبع الحالات
- 👥 إدارة المستخدمين
- 🎯 إدارة العروض والخصومات
- 🖼️ إدارة البنرات الإعلانية
- ⚙️ إعدادات المطعم

## 🛠️ التقنيات

- **Frontend**: Next.js 14 (App Router), React, TypeScript
- **Styling**: Tailwind CSS + Custom Animations
- **Database**: Prisma ORM + SQLite
- **Authentication**: NextAuth.js
- **Icons**: Lucide React
- **Notifications**: React Hot Toast
- **Date Handling**: date-fns
- **Dark Mode**: CSS Variables + localStorage

## ⚡ التشغيل السريع

### المتطلبات
- Node.js 18+
- npm أو yarn

### التثبيت

```bash
# 1. استنساخ المشروع
git clone https://github.com/YOUR_USERNAME/shik-shak-restaurant.git
cd shik-shak-restaurant

# 2. تثبيت المكتبات
npm install

# 3. نسخ ملف البيئة
cp .env.example .env.local

# 4. إعداد قاعدة البيانات
npx prisma generate
npx prisma db push
node prisma/seed.js

# 5. تشغيل المشروع
npm run dev
```

افتح المتصفح على: `http://localhost:3000`

## 🔑 Default Login Credentials

| Role | Email | Password |
|------|-------|----------|
| **Admin** | admin@example.com | demo123 |
| **Customer** | customer@example.com | demo123 |

## 📍 Restaurant Information

- 📞 **Phone**: +970 599 123 456
- 📧 **Email**: info@urbanbites.com
- 📍 **Address**: Ramallah, Palestine
- ⏰ **Working Hours**: Daily 10:00 AM - 12:00 AM
- 💰 **Currency**: Dollar ($)
- 🚚 **Delivery**: Fast delivery service

## 📦 Menu

| Category | Items | Price |
|----------|-------|-------|
| 🍔 **Burgers** | Beef, Chicken | $10-18 |
| 🍕 **Pizza** | 5 types available | $12-17 |
| 🍗 **Chicken** | Meals with sides | $9-25 |
| 🌯 **Wraps** | Various options | $7-10 |
| 🥤 **Drinks** | Fresh & cold | $2-6 |

## 📁 Project Structure

```
urban-bites-restaurant/
├── app/                    # Next.js Pages (App Router)
│   ├── admin/             # لوحة التحكم الإدارية
│   ├── api/               # API Routes
│   ├── products/          # صفحات المنتجات
│   ├── cart/              # سلة التسوق
│   ├── checkout/          # إتمام الطلب
│   ├── globals.css        # Styles عامة + Dark Mode
│   └── ...
├── components/            # مكونات React قابلة لإعادة الاستخدام
│   ├── Navbar.tsx         # شريط التنقل + Dark Mode Toggle
│   ├── Footer.tsx         # تذييل الصفحة
│   ├── DarkModeToggle.tsx # زر Dark Mode
│   └── ...
├── lib/                   # مكتبات ووظائف مساعدة
├── prisma/               # قاعدة البيانات
│   ├── schema.prisma     # Schema
│   └── seed.js           # بيانات تجريبية
├── public/               # ملفات ثابتة (صور، أيقونات)
│   └── images/           # الصور واللوجو
├── types/                # TypeScript Type Definitions
├── .env.example          # مثال لمتغيرات البيئة
├── .gitignore            # ملفات مستثناة من Git
├── GITHUB_GUIDE.md       # دليل الرفع على GitHub
├── CONTRIBUTING.md       # دليل المساهمة
├── CHANGELOG.md          # سجل التغييرات
└── README.md             # هذا الملف
```

## 🚀 النشر

### Vercel (موصى به) ⭐

1. ارفع المشروع على GitHub ([دليل مفصل](GITHUB_GUIDE.md))
2. اذهب إلى [vercel.com](https://vercel.com)
3. استورد المشروع من GitHub
4. أضف متغيرات البيئة
5. اضغط Deploy

### متغيرات البيئة المطلوبة

```env
DATABASE_URL="file:./prisma/dev.db"
NEXTAUTH_SECRET="your-secret-key"
NEXTAUTH_URL="https://your-domain.vercel.app"
```

## 🎨 التخصيص

### تغيير الألوان

عدّل `tailwind.config.ts`:

```typescript
colors: {
  primary: {
    600: '#your-color',
    // ...
  },
}
```

### تعطيل Dark Mode

احذف `<DarkModeToggle />` من `components/Navbar.tsx`

### تغيير Animations

عدّل `app/globals.css` في قسم `@keyframes`

## 🤝 المساهمة

نرحب بمساهماتك! اقرأ [دليل المساهمة](CONTRIBUTING.md) للمزيد من التفاصيل.

## 📝 سجل التغييرات

راجع [CHANGELOG.md](CHANGELOG.md) لمعرفة التغييرات في كل إصدار.

## 📄 الترخيص

هذا المشروع مرخص تحت [MIT License](LICENSE)

## 🙏 شكر وتقدير

- تم البناء بـ [Next.js](https://nextjs.org/)
- التصميم بـ [Tailwind CSS](https://tailwindcss.com/)
- الأيقونات من [Lucide](https://lucide.dev/)

## 📞 التواصل

للاستفسارات والدعم:
- 📧 Email: info@urbanbites.com
- 📱 Phone: +970 599 123 456

## 🔗 روابط مفيدة

- 📚 [دليل الرفع على GitHub](GITHUB_GUIDE.md)
- 🤝 [دليل المساهمة](CONTRIBUTING.md)
- 📝 [سجل التغييرات](CHANGELOG.md)
- 🚀 [Vercel Deployment](https://vercel.com/docs)

---

<div align="center">

**صُنع بـ ❤️ في فلسطين 🇵🇸**

إذا أعجبك المشروع، لا تنسى إضافة ⭐ على GitHub!

[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/shik-shak-restaurant?style=social)](https://github.com/YOUR_USERNAME/shik-shak-restaurant)

</div>

