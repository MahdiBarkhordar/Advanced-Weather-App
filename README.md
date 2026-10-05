<div align="center">

# Weather App · آب‌وهوا

**A live, animated weather dashboard in a single HTML file — 16 languages, 20 backgrounds, a weather-driven living backdrop and a full settings system.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Open-Meteo](https://img.shields.io/badge/Data-Open--Meteo-2563eb)
![No API key](https://img.shields.io/badge/API%20key-not%20required-3fb67a)

[English](#english) · [فارسی](#فارسی)

</div>

---

## English

### Overview
Weather App is a minimal, professional weather dashboard built with vanilla HTML, CSS and JavaScript — no framework, no build step, no API key. Search any city, watch the page react to the real weather (rain, snow, stars, clouds, fog, lightning), and tune almost everything from a built-in settings panel.

### Features

**Weather**
- Current conditions, feels-like, humidity, pressure, UV, visibility, cloud cover and dew point
- Hourly forecast (12 / 24 / 48 h) and daily forecast (7 / 10 / 14 days)
- Hourly trend chart with 4 modes: temperature, feels-like, rain chance, wind
- 24-hour precipitation bars with total rainfall
- Wind compass with direction, gusts and Beaufort scale
- Sun arc (sunrise, sunset, daylight length) and moon phase
- Air quality (European AQI, PM2.5, PM10, NO₂, O₃)
- Automatic alerts: heat, freezing, strong wind, high UV, thunderstorm, heavy rain, poor air quality
- Daily advice: what to wear and activity scores (running, cycling, car wash, line drying)

**Cities**
- Search with live suggestions, flags, population and keyboard navigation
- Favorite cities with live temperatures, recent searches, GPS location
- Shareable link for any city (`#lat,lon,name`)

**Look & feel**
- Floating pill header that shrinks on scroll, quick °C / °F switch with tooltips
- Load animations, scroll-reveal, count-up temperature, chart drawing, skeleton loading
- Weather-driven background: canvas particles (rain, snow, stars, shooting stars, lightning, clouds, fog) plus floating weather icons
- Ripple effect, toasts and tooltips on interactions
- Hand-drawn SVG icon set — no emoji, no icon library

**Settings (8 tabs)**
- **Look:** 10 style presets (default: *Calm*), 5 themes, accent color with HSL sliders, 16 languages with flags, 9 fonts per language, corner radius, text size, number weight, digit style
- **Background:** 20 still and animated patterns with live previews and an intensity slider
- **Interface:** card style (glass / outline / solid), high contrast, compact mode, flipped columns, temperature-based number color, content width
- **Effects:** live weather background, floating icons, particles, scroll animations, 3D cards, cursor glow, progress bar, animation speed and intensity
- **Mouse:** custom cursor (ring / dot / halo) and scrollbar styles
- **Units:** temperature, wind, pressure, distance, rain, 12/24 h, Jalali or Gregorian calendar, auto refresh
- **Content:** show/hide sections, drag-and-drop ordering, hourly range, forecast days, alert thresholds, startup behavior
- **Data:** export / import settings (JSON), reset, print, built-in **guide** (the animated **!** button next to the title)

### Getting started
```bash
git clone https://github.com/MahdiBarkhordar/weather-app.git
cd weather-app
# open index.html in your browser, or serve it locally:
npx serve .
```
Rename `weather-app.html` to `index.html` if you want it served by default. An internet connection is required for weather data, flags and fonts.

### Keyboard shortcuts
| Key | Action |
|-----|--------|
| `/` | Focus search |
| `,` | Open / close settings |
| `U` | Toggle °C / °F |
| `Esc` | Close panel or dropdown |

### Data sources
- Weather, geocoding and air quality: [Open-Meteo](https://open-meteo.com) (free, no key)
- Country flags: [flagcdn.com](https://flagcdn.com)
- Fonts: [Google Fonts](https://fonts.google.com), loaded on demand per language

### Tech notes
- Single self-contained file; settings are stored in `localStorage`
- Fully responsive, RTL / LTR aware, respects `prefers-reduced-motion`
- Translations: Persian and English are complete; other languages cover the core interface and fall back to English

### Roadmap
- [ ] Precipitation radar map
- [ ] Complete translations for all 16 languages
- [ ] Severe-weather browser notifications
- [ ] PWA / offline support

### Author
Designed and built by **[Mehdi Barkhordar](https://github.com/MahdiBarkhordar)**.

### License
MIT — feel free to use, modify and share.

---

<div dir="rtl">

## فارسی

### معرفی
**آب‌وهوا** یک داشبورد هواشناسی زنده و متحرک است که فقط با HTML، CSS و جاوااسکریپت خالص ساخته شده؛ بدون فریم‌ورک، بدون مرحله‌ی build و بدون نیاز به کلید API. هر شهری را جستجو کن، ببین صفحه با آب‌وهوای واقعی (باران، برف، ستاره، ابر، مه، رعدوبرق) واکنش نشان می‌دهد و تقریباً همه‌چیز را از پنل تنظیمات شخصی‌سازی کن.

### امکانات

**هواشناسی**
- وضعیت فعلی، دمای احساس‌شده، رطوبت، فشار، UV، دید افق، پوشش ابر و نقطه شبنم
- پیش‌بینی ساعتی (۱۲ / ۲۴ / ۴۸ ساعت) و روزانه (۷ / ۱۰ / ۱۴ روز)
- نمودار روند ساعتی با ۴ حالت: دما، احساس‌شده، احتمال بارش و باد
- نمودار بارش ۲۴ ساعت آینده با مجموع بارش
- قطب‌نمای باد با جهت، تندباد و مقیاس بوفورت
- کمان خورشید (طلوع، غروب، طول روز) و فاز ماه
- کیفیت هوا (AQI اروپایی، PM2.5، PM10، NO₂، O₃)
- هشدارهای خودکار: گرما، یخبندان، باد شدید، UV بالا، طوفان، بارش سنگین و آلودگی هوا
- پیشنهاد روزانه: پوشش مناسب و امتیاز دویدن، دوچرخه‌سواری، کارواش و خشک‌کردن لباس

**شهرها**
- جستجو با پیشنهاد زنده، پرچم، جمعیت و پیمایش با کیبورد
- شهرهای مورد علاقه با دمای زنده، جستجوهای اخیر و موقعیت GPS
- پیوند اشتراکی برای هر شهر

**ظاهر و حس استفاده**
- هدر معلق و جمع‌وجور که با اسکرول کوچک می‌شود، با سوییچ سریع °C / °F و تولتیپ
- انیمیشن ورود، ظاهر شدن با اسکرول، شمارش دما، رسم نمودار و اسکلت بارگذاری
- پس‌زمینه‌ی زنده بر اساس هوا: ذرات (باران، برف، ستاره، شهاب، رعدوبرق، ابر، مه) و آیکون‌های معلق
- موج کلیک، توست و تولتیپ برای واکنش به تعامل‌ها
- مجموعه آیکون SVG سفارشی، بدون ایموجی و بدون کتابخانه‌ی آیکون

**تنظیمات (۸ تب)**
- **ظاهر:** ۱۰ سبک آماده (پیش‌فرض: آرام)، ۵ تم، رنگ تأکیدی با اسلایدر HSL، ۱۶ زبان با پرچم، ۹ فونت برای هر زبان، گوشه‌ها، اندازه‌ی متن، ضخامت عدد و نوع ارقام
- **پس‌زمینه:** ۲۰ طرح ثابت و متحرک با پیش‌نمایش زنده و اسلایدر شدت
- **رابط:** سبک کارت (شیشه‌ای، خطی، توپر)، کنتراست بالا، حالت فشرده، جابه‌جایی ستون‌ها، رنگ عدد بر اساس دما و عرض محتوا
- **جلوه‌ها:** پس‌زمینه‌ی زنده، آیکون‌های معلق، ذرات، انیمیشن اسکرول، کارت سه‌بعدی، درخشش ماوس، نوار پیشرفت و سرعت و شدت انیمیشن
- **ماوس:** نشانگر سفارشی (حلقه، نقطه، هاله) و سبک اسکرول‌بار
- **واحدها:** دما، باد، فشار، فاصله، بارش، ساعت ۱۲/۲۴، تقویم شمسی یا میلادی و به‌روزرسانی خودکار
- **محتوا:** نمایش یا پنهان‌کردن بخش‌ها، ترتیب با درگ‌اندرداپ، بازه‌ی ساعتی، تعداد روزها، آستانه‌ی هشدارها و رفتار شروع برنامه
- **داده‌ها:** خروجی و ورودی تنظیمات (JSON)، بازنشانی، چاپ و **راهنمای** داخلی (دکمه‌ی متحرک **!** کنار عنوان)

### شروع سریع
```bash
git clone https://github.com/MahdiBarkhordar/weather-app.git
cd weather-app
# فایل index.html را در مرورگر باز کن یا با سرور محلی اجرا کن:
npx serve .
```
اگر می‌خواهی صفحه به‌صورت پیش‌فرض باز شود، نام `weather-app.html` را به `index.html` تغییر بده. برای دریافت داده‌ی هوا، پرچم‌ها و فونت‌ها اینترنت لازم است.

### میان‌برها
| کلید | عملکرد |
|------|--------|
| `/` | رفتن به جستجو |
| `,` | باز و بسته کردن تنظیمات |
| `U` | تغییر °C / °F |
| `Esc` | بستن پنل یا منوی کشویی |

### منابع داده
- هواشناسی، جستجوی شهر و کیفیت هوا: [Open-Meteo](https://open-meteo.com) (رایگان و بدون کلید)
- پرچم کشورها: [flagcdn.com](https://flagcdn.com)
- فونت‌ها: [Google Fonts](https://fonts.google.com) که برای هر زبان به‌صورت درخواستی بارگذاری می‌شوند

### نکات فنی
- یک فایل مستقل؛ تنظیمات در `localStorage` ذخیره می‌شوند
- کاملاً واکنش‌گرا، سازگار با RTL و LTR و پشتیبان `prefers-reduced-motion`
- ترجمه‌ی فارسی و انگلیسی کامل است؛ زبان‌های دیگر بخش‌های اصلی رابط را پوشش می‌دهند و بقیه به انگلیسی برمی‌گردند

### برنامه‌ی آینده
- [ ] نقشه‌ی رادار بارش
- [ ] ترجمه‌ی کامل هر ۱۶ زبان
- [ ] اعلان مرورگر برای هوای نامساعد
- [ ] پشتیبانی PWA و حالت آفلاین

### سازنده
طراحی و ساخت: **[مهدی برخوردار](https://github.com/MahdiBarkhordar)**

### مجوز
MIT — آزادانه استفاده، ویرایش و منتشر کن.

</div>
