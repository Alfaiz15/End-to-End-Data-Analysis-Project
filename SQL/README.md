# 📦 Data-Driven Logistics: Otomasi dan Analisis Gudang (SQL Focused)

## 📌 Ringkasan Proyek

Proyek ini mendemonstrasikan kapabilitas **Data Analyst** dalam perancangan struktur *database* logistik dan implementasi solusi **Otomasi Operasional** menggunakan **Advanced SQL**. Tujuannya adalah memastikan akurasi data inventaris dan menyediakan metrik profitabilitas gudang yang andal untuk pengambilan keputusan manajemen.

## 🛠️ Tools dan Data

* **Primary Tool:** SQL (MySQL/MariaDB)
* **Output:** Stored Procedures, Views, dan *Query* Analisis Kinerja.
* **Fokus Operasional:** Inventory Management, Supply Chain Efficiency, dan Profitability Analysis.

---

## ⚙️ Workflow & Implementasi SQL

Proyek ini dibagi menjadi tiga pilar utama, menunjukkan penguasaan terhadap *data modeling* dan *data engineering* di SQL.

### 1. Data Structure Design (Schema & Integrity)

* **Tugas:** Perancangan skema database (`warehouse_db`) dengan tabel utama: `warehouses`, `products`, `inventory`, dan `shipments`.
* **Keahlian SQL:** Penggunaan `CREATE TABLE` dan definisi **Foreign Keys** untuk menjamin integritas data (konsistensi hubungan antar tabel) dan mencegah *data redundancy*.

### 2. Analytical Engine (Advanced Querying)

Menciptakan mesin analisis untuk menghitung KPI yang kompleks bagi tim *Operations* dan *Finance*.

| Metrik Kunci | Teknik SQL | Manfaat Bisnis |
| :--- | :--- | :--- |
| **Net Profit Gudang** | Menggunakan **Common Table Expressions (CTEs)** untuk memisahkan perhitungan *total revenue* dan *total expense* sebelum dihitung selisihnya. | Menentukan *Profit Center* dan *Cost Center* yang sebenarnya di antara berbagai gudang. |
| **Kinerja Supplier** | Menggunakan `JOIN` dan `GROUP BY` untuk menganalisis rata-rata waktu pengiriman (*lead time*) per pemasok. | Mengidentifikasi *supplier* yang paling efisien, membantu optimalisasi rantai pasok. |

### 3. Business Automation (Procedures & Views)

Mengimplementasikan solusi otomasi untuk meminimalkan intervensi manual dalam *inventory management*.

| Solusi SQL | Deskripsi Teknis | Manfaat Operasional |
| :--- | :--- | :--- |
| **View Stok Rendah (`vw_low_stock`)** | Membuat **VIEW** yang otomatis menampilkan produk dengan kuantitas di bawah batas kritis (`< 100`). | Bertindak sebagai **Sistem Peringatan Dini**. Mempercepat proses *restock* dan mencegah kerugian akibat *stock-out*. |
| **Stored Procedure (`sp_update_stock`)** | Merancang **Stored Procedure** yang mengotomasi penambahan/pengurangan stok (*update inventory*) berdasarkan input transaksi. | **Akurasi Data *Real-time*.** Memastikan konsistensi stok dan mengurangi kesalahan manusia (human error). |

---

## 💡 Dampak & Kesimpulan

Proyek ini membuktikan kemampuan saya dalam **mengubah kebutuhan operasional menjadi solusi data yang terstruktur**. Penggunaan *Advanced SQL* (CTEs, Views, Stored Procedures) secara langsung meningkatkan akurasi inventaris, memfasilitasi analisis profitabilitas yang cepat, dan menunjang *Supply Chain Efficiency* secara keseluruhan.
