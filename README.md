
<div align="center">

# 📦 G.D.S — Gestion De Stock

**تطبيق ذكي لتسيير المخزون، تتبع المبيعات والديون للمحلات التجارية**

![Version](https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-FastAPI-009688?style=for-the-badge&logo=fastapi)
![Android](https://img.shields.io/badge/Android-Java-3DDC84?style=for-the-badge&logo=android)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql)
![HTML CSS JS](https://img.shields.io/badge/Web-HTML%2FCSS%2FJS-F7DF1E?style=for-the-badge&logo=javascript)

</div>

---

## 🧾 وصف المشروع

**G.D.S** هو تطبيق متكامل لتسيير المخزون مصمم خصيصاً للمحلات التجارية.  
يتيح متابعة المبيعات، إدارة الديون، واستقبال تنبيهات فورية عند نقص البضاعة — كل هذا من خلال واجهة ويب أو تطبيق Android.

--المميزات تاع تطبيق 

| الميزة | الوصف |
|--------|-------|
| 📊 **تتبع المبيعات** | سجل كامل لكل عملية بيع مع التاريخ والتفاصيل |
| 🛒 **تتبع المشتريات** | تاريخ كامل للبضاعة المشتراة |
| 💸 **إدارة الديون** | متابعة ديون الزبائن والموردين |
| 🔔 **تنبيهات المخزون** | إشعار تلقائي عند اقتراب نفاد سلعة |
| 📄 **تقارير PDF** | توليد تقارير تلقائية بصيغة PDF |
| 📱 **تطبيق Android** | إدارة المخزون من هاتفك في أي وقت |

---

## 🛠️ التقنيات المستخدمة

### Backend
- **Python** + **FastAPI** — بناء API سريع وموثوق
- **MySQL** — قاعدة البيانات الرئيسية

### Frontend (Web)
- **HTML / CSS / JavaScript** — واجهة ويب سهلة الاستخدام

### Mobile
- **Java (Android)** — تطبيق موبايل لنظام Android

---

## 🗂️ هيكل تاع المشروع

```
G.D.S/
├── backend/
│   ├── main.py
│   ├── models/
│   ├── routes/
│   └── database.py
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── app.js
├── android/
│   └── app/src/...
└── README.md
```

---

## 🚀 كيفاش نشغلو

### 1. Backend (FastAPI)

```bash
# تثبيت المكتبات
pip install -r requirements.txt

# تشغيل السيرفر
uvicorn main:app --reload
```

### 2. قاعدة البيانات (MySQL)

```sql
CREATE DATABASE gds_db;
```

ثم عدّل إعدادات الاتصال في ملف `database.py`

### 3. Frontend

افتح ملف `frontend/index.html` في المتصفح أو شغّله مع سيرفر محلي.

### 4. Android

افتح مجلد `android/` في **Android Studio** وشغّل التطبيق.

---


---

## 👤 المطور

**اسمك** — [@ibdhoussam-web

---

<div align="center">



</div>
# G.D.S