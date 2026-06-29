# پنل توصیف عملکرد - نسخه دسکتاپ ویندوز

یه نرم‌افزار ویندوز برای مدیریت توصیف عملکرد دانش‌آموزان

## ✨ قابلیت‌ها

- 📚 توصیف عملکرد پایه‌های اول تا ششم
- ✏️ ویرایش و ذخیره توصیف‌ها
- 🔗 اشتراک‌گذاری با UUID
- 📥 دانلود فایل Word
- 🌐 اتصال به کد ورکر Cloudflare
- 🔐 پنل معلم با رمز عبور

## 🚀 نحوه ساخت فایل exe

### مرحله ۱: نصب Node.js
از سایت [nodejs.org](https://nodejs.org) نسخه Windows رو دانلود و نصب کن.

### مرحله ۲: دانلود پروژه
```bash
git clone https://github.com/naderuser/panelvip-desktop.git
cd panelvip-desktop
```

### مرحله ۳: نصب پکیج‌ها
```bash
npm install
```

### مرحله ۴: ساخت exe
```bash
npm run build:win
```

فایل exe در پوشه `dist` ساخته میشه.

## 🎮 نحوه استفاده

### روش ۱: بدون نصب (Portable)
فایل exe رو اجرا کن و استفاده کن!

### روش ۲: نصب کامل
روی فایل installer دابل‌کلیک کن و نصب کن.

## 🔧 تنظیمات

### ورود به پنل معلم
- رمز عبور: `nader0933`

### تنظیم آدرس کد ورکر
بعد از ورود، آدرس کد ورکر خودت رو وارد کن:
```
https://tosifa-worker.xxx.workers.dev
```

## 📁 ساختار پروژه

```
panelvip-desktop/
├── main.js          # فایل اصلی Electron
├── preload.js       # فایل preload برای امنیت
├── index.html       # رابط کاربری
├── package.json     # تنظیمات پروژه
└── README.md        # این فایل
```

## 💡 نکات

- برای ساخت exe حتماً باید Node.js نصب باشه
- آنتی‌ویروس ممکنه اول بار اخطار بده ( normal (Accept)
- رمز پیش‌فرض معلم: `nader0933`

## 🤝 ساخته شده با

- Electron
- JavaScript
- HTML/CSS
