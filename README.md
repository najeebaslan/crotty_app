# crotty
The recharge cards app provides an innovative solution for purchasing recharge cards digitally without the need for physical cards, with additional features such as:  ✔ Track past purchases ✔ Exclusive offers ✔ Receive cards instantly on your mobile ✔ Avoid the hassle of losing cards

![](https://img.shields.io/badge/version-1.0.0-blue)
![](https://img.shields.io/badge/flutter-3.19.5-blue)
![](https://img.shields.io/badge/dart-3.3.0-blue)

<!-- PROJECT LOGO -->
<div align="center">
  <img src="assets/logo.png" alt="Logo" width="200">
  
  <h1>تطبيق إدارة كروت الشحن</h1>
  
  <p>
    نظام متكامل لإدارة كروت الشحن لمقدمي الخدمة والعملاء
  </p>

  <div>
    <a href="#">
      <img src="https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white" height="60">
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" height="60">
    </a>
  </div>
</div>

## 📱 لقطات التطبيق

<div align="center">
  <table>
    <tr>
      <td><img src="screenshots/login.jpg" width="200"></td>
      <td><img src="screenshots/home.jpg" width="200"></td>
      <td><img src="screenshots/cards.jpg" width="200"></td>
      <td><img src="screenshots/map.jpg" width="200"></td>
    </tr>
    <tr>
      <td><img src="screenshots/reports.jpg" width="200"></td>
      <td><img src="screenshots/notifications.jpg" width="200"></td>
      <td><img src="screenshots/profile.jpg" width="200"></td>
      <td><img src="screenshots/dark_mode.jpg" width="200"></td>
    </tr>
  </table>
</div>

## ✨ المميزات الرئيسية

### لوحة تحكم المشرف
- 📊 لوحة تحكم متكاملة مع تقارير المبيعات
- 📍 تحديد مناطق التغطية على الخريطة
- 📦 إدارة فئات الكروت والعروض
- 📁 استيراد كروت عبر ملفات CSV

### تجربة العميل
- 🔍 اكتشاف الشبكات القريبة
- 💳 شراء كروت شحن فورية
- 📨 استلام الكروت رقمياً على الجوال
- 📝 سجل المشتريات والتقارير

## 🛠️ التقنيات المستخدمة

### واجهة المستخدم
| التقنية | الوصف |
|---------|-------|
| <img src="https://cdn.iconscout.com/icon/free/png-256/flutter-2038877-1720090.png" width="20"> Flutter | إطار عمل متعدد المنصات |
| 🎨 BLoC Pattern | إدارة الحالة |
| 📱 Responsive UI | واجهات متجاوبة |
| ✨ Lottie Animations | رسوم متحركة عالية الأداء |

### الباك إند
| التقنية | الوصف |
|---------|-------|
| <img src="https://cdn.iconscout.com/icon/free/png-256/node-js-1174925.png" width="20"> Node.js | بيئة تشغيل JavaScript |
| 🗃️ MongoDB | قاعدة بيانات NoSQL |
| 🔥 Redis | التخزين المؤقت |
| 🔐 JWT | المصادقة |

### خدمات إضافية
| التقنية | الوصف |
|---------|-------|
| <img src="https://cdn.iconscout.com/icon/free/png-256/google-maps-2038785-1718337.png" width="20"> Google Maps | تحديد المواقع |
| 🔔 Firebase Messaging | الإشعارات الفورية |
| 📧 SMTP | إرسال البريد الإلكتروني |

## 🏗️ الهيكل التقني

```mermaid
graph TD
  A[Flutter Client] --> B[Node.js Server]
  B --> C[MongoDB]
  B --> D[Redis]
  A --> E[Google Maps]
  A --> F[Firebase Messaging]
  C --> G[Card Inventory]
  C --> H[Sales Reports]
