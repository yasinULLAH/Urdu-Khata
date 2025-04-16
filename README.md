# Urdu Receipt & Khata System (رسید اور کھاتہ سسٹم)

A single-file, offline-first Point-of-Sale (POS) and Khata (ledger) application designed specifically for small businesses operating in Urdu. Built entirely with HTML, CSS, and vanilla JavaScript, using IndexedDB for local data storage.

یہ ایک سنگل فائل، آف لائن پوائنٹ آف سیل (POS) اور کھاتہ (لیجر) ایپلیکیشن ہے جو خاص طور پر اردو بولنے والے چھوٹے کاروباروں کے لیے ڈیزائن کی گئی ہے۔ یہ مکمل طور پر HTML، CSS، اور ونیلا جاوا اسکرپٹ سے بنائی گئی ہے، اور مقامی ڈیٹا اسٹوریج کے لیے IndexedDB کا استعمال کرتی ہے۔


## ✨ Features (خصوصیات)

* **Urdu Interface:** Fully right-to-left interface with Urdu labels and text. (مکمل طور پر دائیں سے بائیں انٹرفیس اردو لیبلز اور متن کے ساتھ۔)
* **Offline Functionality:** All data is stored locally in your browser using IndexedDB. No internet connection required after loading the file. (تمام ڈیٹا IndexedDB کا استعمال کرتے ہوئے آپ کے براؤزر میں مقامی طور پر محفوظ کیا جاتا ہے۔ فائل لوڈ کرنے کے بعد انٹرنیٹ کنکشن کی ضرورت نہیں۔)
* **Single File:** The entire application is contained within a single HTML file for easy distribution and use. (پوری ایپلیکیشن آسان تقسیم اور استعمال کے لیے ایک ہی HTML فائل میں موجود ہے۔)
* **Receipt Generation:** Create and print receipts styled to resemble a traditional Urdu paper receipt. (روایتی اردو کاغذی رسید کی طرح اسٹائل شدہ رسیدیں بنائیں اور پرنٹ کریں۔)
* **Inventory Management:** Add, edit, and delete inventory items with names, descriptions, and rates. (ناموں، تفصیلات اور نرخوں کے ساتھ انوینٹری آئٹمز شامل کریں، ترمیم کریں اور حذف کریں۔)
* **Customer Management:** Maintain a list of customers (in Urdu/English). (کسٹمرز کی فہرست برقرار رکھیں۔)
* **Khata System:** Track individual customer balances (ledgers) with transaction history (purchases and payments). (ٹرانزیکشن ہسٹری (خریداری اور ادائیگی) کے ساتھ انفرادی کسٹمر بیلنس (کھاتہ) ٹریک کریں۔)
* **Payment Tracking:** Record full, partial, or credit (no payment) transactions, automatically updating the customer's khata. (مکمل، جزوی، یا ادھار لین دین ریکارڈ کریں، خود بخود کسٹمر کا کھاتہ اپ ڈیٹ کریں۔)
* **Reporting:** Basic reports including total sales and dues, with filtering by customer or date. (کل فروخت اور واجبات سمیت بنیادی رپورٹس، کسٹمر یا تاریخ کے لحاظ سے فلٹرنگ کے ساتھ۔)
* **Data Management:** Export all application data (inventory, customers, receipts, transactions) to a JSON file for backup and import data from a backup file. (بیک اپ کے لیے تمام ایپلیکیشن ڈیٹا کو JSON فائل میں ایکسپورٹ کریں اور بیک اپ فائل سے ڈیٹا امپورٹ کریں۔)
* **Print Friendly:** Receipts are formatted for easy printing. (رسیدیں آسان پرنٹنگ کے لیے فارمیٹ کی گئی ہیں۔)

## 🛠️ Technology Stack (ٹیکنالوجی)

* HTML5
* CSS3
* Vanilla JavaScript (ES6+)
* IndexedDB API (Browser Storage)

## 🚀 How to Use (استعمال کرنے کا طریقہ)

1.  Download the `your_app_filename.html` file from this repository.
2.  Open the downloaded HTML file in your web browser (like Chrome, Firefox, Edge).
3.  The application will load, and you can start using it immediately. All data will be saved within that browser on your computer.

(1. اس ریپوزٹری سے `your_app_filename.html` فائل ڈاؤن لوڈ کریں۔)
(2. ڈاؤن لوڈ کی گئی HTML فائل کو اپنے ویب براؤزر (جیسے کروم، فائر فاکس، ایج) میں کھولیں۔)
(3. ایپلیکیشن لوڈ ہو جائے گی، اور آپ اسے فوراً استعمال کرنا شروع کر سکتے ہیں۔ تمام ڈیٹا آپ کے کمپیوٹر پر اسی براؤزر میں محفوظ ہو جائے گا۔)

## ⚠️ Limitations (حدود)

* **Browser Dependent:** Data is stored locally in the specific browser you use. Clearing browser data will erase the application's data unless backed up.
* **Single User:** Designed for use by a single user on a single computer.
* **No Cloud Sync:** Data is not automatically backed up or synced across devices. Use the Export feature regularly for backups.
* **Styling:** Styling aims to match the provided receipt but might vary slightly depending on the browser and available system fonts.

## 🙏 Feedback (تاثرات)

Feedback and suggestions are welcome! Feel free to open an issue in this repository.
