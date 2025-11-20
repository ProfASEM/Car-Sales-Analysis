
# Car Sales Analysis Dashboard 🚗📊

A comprehensive data analysis project exploring car sales performance, pricing patterns, engine specifications, and resale value retention across various manufacturers and models. This project has been upgraded to feature **interactive Power BI dashboards** alongside the initial Excel analysis.

---

## 📊 Project Overview
This project analyzes a dataset of car sales, combining performance, pricing, fuel efficiency, and vehicle specifications.
The goal is to extract insights, identify patterns, and visualize important trends using **Excel** for data processing and **Power BI** for advanced, interactive storytelling.

---

## 📁 Project Structure
```text
Car-Sales-Analysis/
│
├── data/
│   └── Car Sales Analysis.xlsx
│
├── dashboards/
│   └── Car Sales Dashboard.pbix
│
├── images/
│   ├── Dashboard Main.png
│   ├── Dashboard EU.png
│   ├── Dashboard Asia.png
│   ├── Dashboard USA.png
│   ├── line-chart.png
│   ├── bar-chart.png
│   └── scatter-plot.png
│
└── README.md
````

-----

## 📑 Dataset Description

The dataset includes the following key attributes:

  - **Manufacturer** — Car brand
  - **Model** — Model name
  - **Unit Sales** — Number of cars sold
  - **Price** — Selling price
  - **Resale Value** — Value after latest launch year
  - **Retention %** — Percentage of resale value retained
  - **Engine Metrics** — Engine Size, Horsepower, Fuel Efficiency
  - **Vehicle Type** — Passenger, Car, Truck, etc.

-----

## 🧹 Data Preparation

  - Checked for missing values & data consistency.
  - Created custom columns in Power BI (DAX) for calculated metrics.
  - Categorized **Retention Value** into groups (Good/Poor).
  - Modeled relationships between data tables for dynamic filtering.

-----

## 📈 Analysis & Visualizations

### 🚀 1. Power BI Dashboards (New Update)

The project has been upgraded with a multi-page interactive report featuring a **Dark Mode** design.

#### **🔹 Main Dashboard (Global View)**

  - **Key KPIs:** Total Sales ($ Billions) & Unit Sales.
  - **Correlation Heatmap:** Analyzes relationships between Price, Engine Size, Horsepower, and Fuel Capacity.
  - **Retention Analysis:** Donut chart showing the distribution of resale value retention.
  - **Global Sales by Manufacturer:** Bar chart ranking top brands.

\<div align="center"\>
\<img src="images/Dashboard Main.png" width="800"\>
\</div\>

<br>

#### **🔹 Regional Dashboards (Asia, EU, USA)**

  - **Treemaps:** Visualizing top 10 models' unit sales per region.
  - **Scatter Plots:** Comparing **Price vs. Year Resale Value** (Bubble size = Sales volume).
  - **Sales Trends:** Area/Ribbon charts showing sales performance over time or across models.
  - **Engine Distribution:** Unit sales distribution by Horsepower and Engine Size.

\<p align="center" float="left"\>
\<img src="images/Dashboard USA.png" width="260" /\>
\<img src="images/Dashboard EU.png" width="260" /\>
\<img src="images/Dashboard Asia.png" width="260" /\>
\</p\>

-----

### 📊 2. Excel Charts (Initial Analysis)

  - **Line Charts:** Tracking trends.
  - **Scatter Plots:** Initial exploration of Price vs. Value.
  - **Sunburst & Histograms:** Distribution analysis.

-----

## 🔍 Key Insights

  - **Price vs. Power:** Strong positive correlation (0.85) between Horsepower and Price, verified by the Heatmap.
  - **Resale Value:** Asian manufacturers (e.g., Toyota, Honda) show strong retention rates compared to competitors in the same price range.
  - **Regional Preferences:**
      - **USA:** Strong preference for high-horsepower vehicles (Ford F-Series).
      - **Europe:** Higher sales concentration in compact and mid-sized efficient luxury cars.

-----

## 🛠 Tools Used

  - **Microsoft Power BI** (Dashboards, DAX, Data Modeling)
  - **Microsoft Excel** (Pivot Tables, Initial Charts)

-----

## 📌 Future Improvements

  - Build a predictive model (Machine Learning) to forecast car prices.
  - Add Python scripts for deeper statistical analysis.
  - Automate data refreshing using Power BI Service.

<br>
<br>

# ——————————————————————————————————————————

<br>

# 🇸🇦🇦🇪 تحليل مبيعات السيارات — لوحة بيانات تفاعلية

مشروع تحليلي شامل لبيانات مبيعات السيارات، يهدف إلى فهم سلوك الأسعار، أداء الموديلات، ومواصفات المحركات، مع التركيز الآن على **لوحات المعلومات التفاعلية (Dashboards)** لتقديم رؤى أعمق.

-----

## 📊 نظرة عامة على المشروع

يعتمد المشروع على تحليل بيانات السيارات لاستخراج الأنماط والاتجاهات. تم تطوير العمل لينتقل من التحليل التقليدي باستخدام Excel إلى بناء **قصص بيانية تفاعلية باستخدام Power BI**.

-----

## 📁 هيكل المشروع

تم إضافة مجلد خاص بملفات Power BI وصور اللوحات الجديدة كما هو موضح في القسم الإنجليزي أعلاه.

-----

## 📑 وصف البيانات

تشمل البيانات: الشركة المصنعة، الموديل، المبيعات، السعر، قيمة إعادة البيع، نسبة الاحتفاظ بالقيمة، ومواصفات المحرك (الحجم، القوة، الكفاءة).

-----

## 📈 التحليل والرسوم البيانية

### 🚀 1. لوحات Power BI (تحديث جديد)

تم تصميم تقرير متعدد الصفحات بنظام **الوضع الداكن (Dark Mode)**:

#### **🔹 اللوحة الرئيسية (Main Dashboard)**

  - **مؤشرات الأداء (KPIs):** إجمالي المبيعات (بالمليار دولار) وعدد الوحدات.
  - **خريطة الارتباط (Correlation Heatmap):** توضح العلاقة القوية بين السعر، القوة الحصانية، وسعة المحرك.
  - **تحليل القيمة:** توزيع نسبة الاحتفاظ بالقيمة (Retention Value).

\<div align="center"\>
\<img src="images/Dashboard Main.png" width="800"\>
\</div\>

<br>

#### **🔹 اللوحات الإقليمية (آسيا، أوروبا، أمريكا)**

  - **الخرائط الشجرية (Treemaps):** تعرض أفضل 10 موديلات مبيعاً في كل منطقة.
  - **مخططات التشتت (Scatter Plots):** علاقة السعر بقيمة إعادة البيع (حجم الدائرة يمثل حجم المبيعات).
  - **توزيع المحركات:** تحليل المبيعات بناءً على القوة الحصانية وحجم المحرك.

\<p align="center" float="left"\>
\<img src="images/Dashboard USA.png" width="260" /\>
\<img src="images/Dashboard EU.png" width="260" /\>
\<img src="images/Dashboard Asia.png" width="260" /\>
\</p\>

-----

### 📊 2. رسوم Excel (التحليل الأولي)

تم استخدام المخططات الخطية، العمودية، وSunburst لاستكشاف البيانات قبل نقلها إلى Power BI.

-----

## 🔍 أهم النتائج

  - **الارتباط:** وجود علاقة قوية جداً (0.85) بين سعر السيارة وقوتها الحصانية.
  - **القيمة:** السيارات الآسيوية (مثل تويوتا وهوندا) تحافظ على قيمة إعادة بيع أعلى مقارنة بالمنافسين.
  - **التفضيلات الإقليمية:** السوق الأمريكي يميل للسيارات ذات القوة الحصانية العالية، بينما السوق الأوروبي يميل للكفاءة والفخامة المدمجة.

-----

## 🛠 الأدوات المستخدمة

  - **Microsoft Power BI** (تصميم اللوحات، معادلات DAX).
  - **Microsoft Excel** (الجداول المحورية Pivot Tables).

-----

## 📌 تطويرات مستقبلية

  - بناء نموذج تعلم آلة (Machine Learning) لتوقع أسعار السيارات.
  - استخدام Python لإجراء تحليلات إحصائية متقدمة.

<!-- end list -->

```
```
