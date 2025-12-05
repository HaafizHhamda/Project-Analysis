# Project Analysis & Dashboard

**Ringkasan singkat**

Anda adalah seorang Data Analyst yang akan mengerjakan sebuah project untuk menyelesaikan permasalahan seorang client. Client Anda membutuhkan hasil analisa data yang menggunakan statistik dan dashboard visualisasi untuk membantu mereka menyelesaikan masalahnya.


---

## Struktur README
1. Problem Statement
2. Objective
3. Data
4. Metode / Alur Pengerjaan
5. Environment
6. Kesimpulan
7. Hasil yang Diharapkan
8. Sumber & Referensi

---

## 1. Problem


Project ini menganalisis tren penjualan bulanan, performa kategori produk, kelompok usia, dan lokasi, dilengkapi statistik deskriptif serta korelasi perilaku pengguna. Seluruh hasil disajikan melalui dashboard interaktif untuk mendukung insight dan pengambilan keputusan bisnis.

---
## 2. Objectives



*Pengerjaan* ini dibuat dengan tujuan sebagai berikut :

- Bagaimana tren penjualan bulanan ?.

- Bagaimana penjualan bedasarkan product category?.

- bagaimana penjualan berdasarkan age category?.

- bagaimana penjualan berdasarkan lokasi?.

- bagaimana statistik deskriptif berdasarkan penjualan

- bagaimana korelasi antara session duration minutes, page view dan quantity?

- membuat dashboard 
---

## 3. Data
*Colums Descriptions*:

- Order_ID
Unique identifier for each transaction. Format: ORD_XXXXXX (6-digit number)
- Customer_ID
Unique identifier for each customer. Format: CUST_XXXXX (5-digit number)
- Date
Transaction date when the order was placed. Range: 2023-01-01 to 2024-03-26
- Age
Customer's age in years. Range: 18-75 years old
- Gender
Customer's gender. Values: Male, Female, Other
- City
Customer's city location in Turkey. 10 major cities included
- Product_Category
Category of purchased product. 8 categories: Electronics, Fashion, Home & Garden, Sports, Books, Beauty, Toys, Food
- Unit_Price
Price per unit of the product in Turkish Lira (TRY). Varies by category
- Quantity
Number of units purchased in the transaction. Range: 1-5 units
- Discount_Amount
Total discount applied to the order in TRY. Zero if no discount applied
- Total_Amount
Final amount paid after discount (Unit_Price × Quantity - Discount_Amount)
- Payment_Method
Method used for payment. Options: Credit Card, Debit Card, Digital Wallet, Bank Transfer, Cash on Delivery
- Device_Type
Device used to make the purchase. Options: Mobile, Desktop, Tablet
- Session_Duration_Minutes
Time spent on website during the session in minutes. Range: 1-120 minutes
- Pages_Viewed
Number of pages viewed during the shopping session. Range: 1-50 pages
- Is_Returning_Customer
Whether the customer has made previous purchases. Values: True (returning) or False (new customer)
- Delivery_Time_Days
Number of days taken to deliver the order. Range: 1-30 days
- Customer_Rating
Customer satisfaction rating for the order. Scale: 1-5 stars (1=very dissatisfied, 5=very satisfied)

---

## 4. Metode / Alur Pengerjaan
1. **Load data**
2. **Data processing**
3. **Analisis deskriptif**
4. **Kesimpulan**.
5. **Make Dashoard**

---

## 5. Environment 
1. Python:
- **Pandas**
- **Matplotlib**
- **Scipy**
2. Tableu

---

## 6. Kesimpulan 
- Berhasil menampilkan tren penjualan bulanan .

- Berhasil menampilkan penjualan bedasarkan product category.

- Berhasil menampilkan penjualan berdasarkan age category.

- Berhasil menampilkan penjualan berdasarkan lokasi.

- Berhasil menampilkan statistik deskriptif berdasarkan penjualan

- Berhasil menampilkan korelasi antara session duration minutes, page view dan quantity

- Berhasil membuat dashboard sederhana
---
## 7. Hasil yang Diharapkan 
- `Pengerjaan.csv` — Data raw dari kaggle.
- Notebook `pengerjaan.ipynb` - Hasil Objective
- [Hasil Dasboard](https://public.tableau.com/views/Dashboard_17649132879160/Dashboard321?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---
## 8. Referensi & Sumber Data

Data diambil dari website:  
 [**kaggle.com**](https://www.kaggle.com/datasets/umuttuygurr/e-commerce-customer-behavior-and-sales-analysis-tr)

---




