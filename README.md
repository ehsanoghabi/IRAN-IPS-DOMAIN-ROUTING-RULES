# IRAN-IPS-DOMAIN-ROUTING-RULES

[**فارسی (Persian)**](#توضیحات-فارسی) | [**English**](#english-description)

---

## English Description

This repository provides a curated and up-to-date list of essential Iranian domains and IP addresses. These lists are specifically designed to be used in network routers and **OpenWrt** systems for traffic separation (Bypass) and policy routing.

By using these lists, you can easily route domestic (Iranian) traffic directly through your local ISP while tunneling international traffic, optimizing your network performance and avoiding unnecessary proxy overhead.

### 📂 Files Included
* `IRAN-IPS.txt`: Contains important Iranian IP subnets.
* `IRAN-Domain.txt`: Contains important Iranian domains (banks, government portals, internal services, etc.).

### 🚀 Usage
You can directly fetch the raw content of these files into your router's configuration using their direct URLs:

* **IPs Raw Link:** `https://raw.githubusercontent.com/ehsanoghabi/
IRAN-IPS-DOMAIN-ROUTING-RULES/main/IRAN-IPS.txt`
* **Domains Raw Link:** `https://raw.githubusercontent.com/ehsanoghabi/
IRAN-IPS-DOMAIN-ROUTING-RULES/main/IRAN-Domain.txt`

#### OpenWrt
You can use these lists in OpenWrt with packages like `pbr` (Policy Based Routing), `mwan3`, `passwall`, `shadowsocks`, or custom `nftables`/`iptables` scripts to bypass local traffic. 

#### General Routers (MikroTik, etc.)
Use the fetch tools (like `/tool fetch` in MikroTik) to download the `.txt` files on a schedule and automatically populate your Address Lists or DNS static entries.

---

## توضیحات فارسی

این مخزن شامل لیست جامع و به‌روزی از دامنه‌ها و آدرس‌های IP مهم و پرکاربرد ایرانی است. این فایل‌ها به صورت اختصاصی برای استفاده در روترهای شبکه و سیستم‌های **OpenWrt** جهت تفکیک ترافیک (Bypass) و مسیریابی هدفمند (Policy Routing) ایجاد شده‌اند.

با استفاده از این لیست‌ها می‌توانید ترافیک داخلی (سایت‌های بانکی، دولتی و سرویس‌های ایرانی) را مستقیماً از اینترنت داخلی عبور داده و تنها ترافیک بین‌الملل را از تونل یا پروکسی عبور دهید تا سرعت و پایداری شبکه افزایش یابد.

### 📂 فایل‌های موجود
* `IRAN-IPS.txt`: شامل لیست ساب‌نت‌ها و آی‌پی‌های مهم ایران.
* `IRAN-Domain.txt`: شامل لیست دامنه‌های مهم ایران.

### 🚀 نحوه استفاده
برای استفاده در روترها، نیازی به دانلود دستی فایل‌ها نیست. شما می‌توانید لینک مستقیم (Raw) فایل‌ها را به اسکریپت‌ها یا پلاگین‌های روتر خود بدهید تا همیشه آخرین نسخه را دریافت کنند:

* **لینک مستقیم آی‌پی‌ها:** `https://raw.githubusercontent.com/ehsanoghabi/
IRAN-IPS-DOMAIN-ROUTING-RULES/main/IRAN-IPS.txt`
* **لینک مستقیم دامنه‌ها:** `https://raw.githubusercontent.com/ehsanoghabi/
IRAN-IPS-DOMAIN-ROUTING-RULES/main/IRAN-Domain.txt`

#### در سیستم‌های OpenWrt
این فایل‌ها به راحتی در پکیج‌های مسیریابی OpenWrt مانند `pbr`، `mwan3`، کلاینت‌های V2ray/Xray (مثل Passwall یا OpenClash) و اسکریپت‌های کاستوم فایروال قابل استفاده هستند.

#### در سایر روترها (مثل میکروتیک)
می‌توانید با استفاده از ابزارهای دانلود خودکار روتر، این فایل‌های متنی را در بازه‌های زمانی مشخص دریافت کرده و به صورت خودکار به Address List ها یا تنظیمات DNS روتر خود اضافه کنید.

---
**Note / توجه:** 
Contributions and updates to the lists are welcome. Please submit a Pull Request!
برای تکمیل و به‌روزرسانی لیست‌ها می‌توانید Pull Request ارسال کنید.
Contributions and updates to the lists are welcome. Please submit a Pull Request!
برای تکمیل و به‌روزرسانی لیست‌ها می‌توانید Pull Request ارسال کنید.
