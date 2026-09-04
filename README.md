
# 📊 Adidas US Interactive Sales Dashboard

## 📌 نبذة عن المشروع (Project Overview)
مشروع تحليل بيانات مبيعات شركة أديداس وتحويل البيانات الخام إلى لوحة تحكم تفاعلية (Interactive Dashboard) باستخدام Pivot Tables و Pivot Charts في Excel لمتابعة المبيعات والأرباح وأداء قنوات التوزيع والمناطق الجغرافية.

---
# 📊 Adidas US Interactive Sales Dashboard overview
<img width="1592" height="545" alt="Screenshot 2026-09-04 093924" src="https://github.com/user-attachments/assets/fc94f1b0-5c50-425a-8042-43fca77cb0be" />

---

## 🛠️ خطوات العمل والتنفيذ (Step-by-Step Workflow)

1. **تجهيز وإعداد البيانات**:
   - تحويل البيانات الخام (Raw Data) إلى **Excel Table** لضمان ديناميكية البيانات.
2. **إنشاء معمارية الـ Pivot Tables**:
   - إنشاء أول **Pivot Table** ونقله إلى ورقة عمل مخصصة للتحليلات (Sheet 2).
3. **تصميم واجهة لوحة التحكم (Layout & UI Design)**:
   - إضافة العنوان الرئيسي وتنسيق الخطوط (Fonts).
   - إدراج صورة علم أمريكا كرمز لنطاق البيانات الجغرافي.
4. **حساب المؤشرات الرئيسية (KPIs)**:
   - إنشاء Pivot Table لحساب **إجمالي الأرباح (Profit)** وتوثيقها على الداشبورد.
   - إنشاء Pivot Table لحساب **عدد الموزعين (Retailers)** وإجمالي الوحدات المباعة.
5. **تحليل اتجاه المبيعات الزمني (Sales Trend)**:
   - إنشاء **Line Chart** يربط إجمالي المبيعات بالأرباع السنوية (Quarters).
6. **التوزيع الجغرافي (Sales Region)**:
   - إنشاء **Map Chart** لعرض المبيعات حسب المناطق والدول.
7. **تحليل قنوات البيع (Sales Methods)**:
   - إنشاء Pivot Table لحساب نسب قنوات البيع (Online, Retail, Outlet, Wholesale) وتمثيلها بـ **Donut Chart**.
8. **ربحية المنتجات (Profit Per Product)**:
   - إنشاء Pivot Table لحساب الربح لكل فئة منتج وتمثيلها بـ **Column Chart**.
9. **التفاعلية والتنسيق النهائي**:
   - إدراج **Slicer** للدول (Country) وربطه بجميع الرسوم البيانية.
   - ضبط الهوامش والألوان والتنسيق البصري للداشبورد.
   - التقاط صورة شاشة (Screenshot) للوحة التحكم النهائية.

---

## 📊 مكونات الداشبورد (Dashboard Visual Components)

| المكون | نوع الرسم (Chart Type) | الهدف التحليلي |
| :--- | :--- | :--- |
| **KPIs** | Summary Cards | عرض إجمالي الأرباح ($85,070)، الوحدات المباعة (3,550)، وعدد الموزعين (5) |
| **Profit Per Product** | Clustered Column | تحليل ربحية الأحذية (رجالي/حريمي)، الملابس، والأكسسوارات |
| **Sales Method** | Donut Chart | نسبة قنوات البيع (Online 46%, Retail 36%, Outlet 12%, Wholesale 6%) |
| **Sales Trend By Quarters** | Line Chart | تتبع اتجاه المبيعات عبر Q1، Q2، Q3، Q4 |
| **Retailers Sales** | Horizontal Bar Chart | أداء الموزعين وتوزيع مبيعاتهم حسب الدول |
| **Sales Region** | Map Chart | خريطة تفاعلية لتوزيع المبيعات جغرافياً |
| **Country Slicer** | Dynamic Slicer | تصفية كافة البيانات والرسوم البيانية بناءً على الدولة |

---

## 🛠️ الأدوات المستخدمة (Tools & Tech Stack)
- **Microsoft Excel**: Pivot Tables, Pivot Charts, Slicers, Map Charts, Custom Formatting.
