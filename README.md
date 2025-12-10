# Analisis Perilaku Pelanggan dan Penjualan E-Commerce

##  Deskripsi Singkat
Project ini bertujuan untuk menganalisis pola perilaku pelanggan dan performa penjualan pada platform e-commerce menggunakan *E-Commerce Customer Behavior and Sales Dataset*. Fokus utama analisis meliputi tren penjualan bulanan, performa kategori produk, segmentasi berdasarkan usia, distribusi penjualan berdasarkan lokasi, statistik deskriptif penjualan, serta korelasi antara aktivitas pengguna (session duration dan page views) terhadap jumlah pembelian.

##  Repository Outline
```
├── README.md                   # Gambaran umum project
├── Notebook.ipynb              # Notebook berisi analisis data & visualisasi
├── Pengerjaan.csv              # Dataset yang akan diproses
└── tableau_dashboard_url.txt   # Link dashboard Tableau
```

##  Problem Background
Pertumbuhan e-commerce yang pesat membuat pemahaman terhadap perilaku pelanggan menjadi hal yang krusial. Dataset ini memberikan insight mengenai pola transaksi, demografi pelanggan, kategori produk, dan aktivitas pengguna. Dengan analisis yang tepat, perusahaan dapat meningkatkan strategi pemasaran, menargetkan pelanggan yang tepat, serta mengoptimalkan pengalaman pengguna.

##  Tujuan Project
- Mengidentifikasi tren penjualan bulanan.
- Menganalisis penjualan berdasarkan kategori produk.
- Melihat performa penjualan berdasarkan kelompok usia.
- Mengukur kontribusi penjualan berdasarkan lokasi.
- Menyajikan statistik deskriptif penjualan.
- Mengukur korelasi antara session duration, page views, dan quantity.

##  Data
Dataset berisi informasi seperti:
- **Order_ID** — Unique identifier per transaksi (Format: ORD_XXXXXX).
- **Customer_ID** — Unique identifier per pelanggan (Format: CUST_XXXXX).
- **Date** — Tanggal transaksi (2023-01-01 sampai 2024-03-26).
- **Age** — Usia pelanggan (18–75).
- **Gender** — Male, Female, Other.
- **City** — 10 kota besar di Turki.
- **Product_Category** — Electronics, Fashion, Home & Garden, Sports, Books, Beauty, Toys, Food.
- **Unit_Price** — Harga satuan (TRY).
- **Quantity** — Jumlah unit (1–5).
- **Discount_Amount** — Diskon total (TRY).
- **Total_Amount** — Total pembayaran setelah diskon.
- **Payment_Method** — Credit Card, Debit Card, Digital Wallet, Bank Transfer, COD.
- **Device_Type** — Mobile, Desktop, Tablet.
- **Session_Duration_Minutes** — Durasi sesi (1–120 menit).
- **Pages_Viewed** — Jumlah halaman yang dilihat (1–50).
- **Is_Returning_Customer** — True/False.
- **Delivery_Time_Days** — Estimasi pengiriman (1–30 hari).
- **Customer_Rating** — Rating 1–5.

##  Method
- Exploratory Data Analysis (EDA)
- Data Cleaning dan Preprocessing
- Visualisasi data (Line Chart, Bar Chart, Table, Pie Chart)
- Analisis statistik deskriptif
- Analisis korelasi antar variabel

##  Tech Stack
- Python (Pandas, Matplotlib, Scipy)
- Tableu
- Jupyter Notebook


##  Output Project
- Laporan analisis data berupa notebook dan visualisasi
- Insight penjualan berdasarkan kategori, waktu, lokasi, dan demografi
- Dashboard Tableau interaktif

##  Referensi Tambahan
- Kaggle untuk dataset
- Dokumentasi Pandas & Matplotlib

