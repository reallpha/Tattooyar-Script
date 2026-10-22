# 🎨 نوبت مارکت | NOBAT MARKET

<div align="center">

### پلتفرم حرفه‌ای بازار و رزرو تتو در ایران

**طراحی و توسعه کامل توسط محمدرضا چنگیزی**

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma)](https://www.prisma.io/)

<br>

**🇮🇷 توسعه‌دهنده ایرانی | Full-Stack Developer**  
🌐 وب‌سایت شخصی: [Web Vision](https://webvision.ir)

</div>

---

## 🔥 معرفی پروژه

**نوبت مارکت** یک پلتفرم کامل SaaS برای اتصال هنرمندان تتو و مشتریان در ایران است.  
از جستجوی هنرمند و رزرو آنلاین گرفته تا پرداخت امن و مدیریت کامل کسب‌وکار، همه چیز در یک جا جمع شده.

این پروژه از صفر تا صد توسط **محمدرضا چنگیزی** طراحی و کدنویسی شده و به عنوان یکی از نمونه‌کارهای اصلی در پورتفولیو قرار گرفته است.

---

## 💎 چرا این پروژه خاص است؟

| ویژگی | توضیح |
|-------|-------|
| 🎯 **کامل‌ترین پلتفرم تتو ایران** | از کشف هنرمند تا پرداخت و مراقبت بعد از تتو |
| 🔒 **امنیت بانکی** | پرداخت زرین‌پال + احراز هویت OTP + JWT |
| 🌑 **طراحی پریمیوم** | رابط تاریک و لوکس با Tailwind + Shadcn UI |
| ⚡ **عملکرد بالا** | Next.js 14 App Router + Sharp + Redis |
| 📈 **SEO قدرتمند** | Sitemap پویا + OpenGraph + ساختار URL بهینه |
| 🧩 **معماری تمیز** | TypeScript کامل + ماژولار و مقیاس‌پذیر |
| 🇮🇷 **پشتیبانی کامل RTL** | بهترین تجربه فارسی و راست‌به‌چپ |
| 📊 **داشبورد حرفه‌ای** | آمار، تحلیل، مدیریت کاربران و محتوا |

---

## ✨ امکانات کلیدی

### 👤 برای مشتریان
- جستجوی پیشرفته هنرمندان (سبک، شهر، قیمت، امتیاز)
- رزرو آنلاین با تقویم تعاملی
- پرداخت امن از طریق زرین‌پال
- چت مستقیم با هنرمند
- ثبت نظر و امتیاز
- ذخیره نمونه‌کارهای مورد علاقه

### 👨‍🎨 برای هنرمندان
- داشبورد مدیریت رزروها
- مدیریت نمونه‌کار و تتوهای فلش
- تنظیم برنامه کاری و زمان‌های در دسترس
- کیف پول و مدیریت درآمد
- دریافت درخواست‌های سفارشی

### 🛠️ برای مدیران
- داشبورد آمار و تحلیل
- مدیریت کاربران و پلن‌ها
- سیستم مدیریت محتوا (CMS)
- مدیریت پرداخت‌ها و برداشت‌ها

---

## 🛠️ تکنولوژی‌های استفاده شده

| لایه | تکنولوژی |
|------|----------|
| **فرانت‌اند** | Next.js 14 (App Router) + React 18 + TypeScript |
| **استایل** | Tailwind CSS + Shadcn UI |
| **بک‌اند** | Next.js Server Actions + Prisma ORM |
| **دیتابیس** | PostgreSQL + Redis |
| **احراز هویت** | NextAuth v4 (OTP + JWT) |
| **پرداخت** | زرین‌پال |
| **پردازش تصویر** | Sharp + Storage (Local / S3) |
| **اعلان‌ها** | کاوه‌نگار (SMS) + Resend (Email) |

---

## 🚀 راه‌اندازی سریع

```bash
# کلون کردن پروژه
git clone https://github.com/YOUR_USERNAME/nobat-market.git
cd nobat-market

# نصب پکیج‌ها
npm install

# کپی فایل محیطی
cp .env.example .env

# راه‌اندازی دیتابیس
npx prisma db push
npm run db:seed

# اجرای پروژه
npm run devپروژه روی آدرس زیر اجرا می‌شود:

👉 http://localhost:3000📁 ساختار پروژهtextsrc/
├── app/
│   ├── (public)/       # صفحات عمومی
│   ├── (client)/       # پنل مشتری
│   ├── (artist)/       # پنل هنرمند
│   ├── (admin)/        # پنل مدیریت
│   └── api/
├── components/
│   ├── ui/             # کامپوننت‌های Shadcn
│   ├── features/       # کامپوننت‌های بیزینس
│   └── layout/
├── lib/
├── services/           # Server Actions
├── types/
└── constants/🔧 دستورات مفیدBashnpm run dev          # اجرای حالت توسعه
npm run build        # بیلد پروژه
npm run start        # اجرای نسخه پروداکشن
npm run lint         # بررسی کد
npm run typecheck    # بررسی تایپ‌ها

npm run db:generate  # تولید Prisma Client
npm run db:push      # اعمال اسکیما
npm run db:seed      # داده‌های نمونه
npm run db:studio    # باز کردن Prisma Studio👨‍💻 درباره‌ی توسعه‌دهندهاین پروژه به‌طور کامل توسط محمدرضا چنگیزی طراحی، کدنویسی و پیاده‌سازی شده است.
🇮🇷 توسعه‌دهنده فول‌استک ایرانی
🌐 وب‌سایت شخصی: Web Vision
💼 تمرکز روی ساخت محصولات واقعی، مقیاس‌پذیر و با کیفیت بالا

ساخته شده با ❤️ توسط محمدرضا چنگیزی
Web Vision

```
