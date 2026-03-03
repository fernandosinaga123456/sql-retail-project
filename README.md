# Retail Business Insights - SQL Data Analysis Project

## Latar Belakang

Bisnis retail menghasilkan data transaksi setiap harinya, namun tidak semua data tersebut dimanfaatkan untuk pengambilan keputusan. Proyek ini hadir untuk menjawab pertanyaan bisnis yang relevan melalui pendekatan berbasis data menggunakan MySQL.

Dengan dataset penjualan retail, proyek ini menganalisis performa brand, identifikasi pelanggan VIP, produk terlaris per kategori, kondisi stok, distribusi geografis pelanggan, hingga perbandingan performa antar toko.

Proyek ini merupakan latihan nyata dalam menulis query SQL untuk menghasilkan insight bisnis yang dapat langsung digunakan sebagai dasar keputusan operasional dan strategis.

---

## Tools & Teknologi

| Tools | Kegunaan |
|---|---|
| MySQL | Joins, aggregations, subqueries, filtering, grouping |

---

## Analisis yang Dilakukan

### 1. Sales Performance by Brands
Identifikasi brand dengan revenue dan volume penjualan tertinggi.

**Key Findings:**
- Trek menghasilkan revenue tertinggi sebesar $5,1 juta dengan harga jual tinggi per unit
- Electra menjadi brand paling laris dengan 2.612 unit terjual namun harga produk lebih terjangkau
- 3 brand terbawah hanya berkontribusi sebesar $13K secara keseluruhan

**Rekomendasi:** Prioritaskan kemitraan dan alokasi stok untuk Trek dan Electra. Evaluasi kembali brand dengan kontribusi rendah.

---

### 2. Top Customer Identification
Menemukan pelanggan VIP berdasarkan total spending dan jumlah order.

**Key Findings:**
- Pamela Newman dari NY adalah pelanggan terbaik dengan total spending $37.801 dari 11 orders
- New York mendominasi top 10 customers, 7 dari 10 pelanggan terbesar berasal dari NY
- Selisih spending antara pelanggan teratas dan terendah di top 10 mencapai $10K

**Rekomendasi:** Buat program loyalitas khusus untuk pelanggan VIP dan fokuskan strategi retensi pada pelanggan NY.

---

### 3. Best Selling Product by Category
Produk terlaris di setiap kategori untuk optimasi stok dan display.

**Key Findings:**
- Electra Girl's Hawaii mendominasi kategori Children Bicycles dengan 2 varian terjual 154 dan 145 unit
- Brand Electra menguasai 80% dari top products keseluruhan kategori
- Produk dengan penjualan di atas 100 unit memerlukan prioritas stok

**Rekomendasi:** Optimalkan display dan alokasi rak untuk produk Electra. Pastikan stok bestseller tidak sampai habis.

---

### 4. Low Stock Alert
Deteksi produk yang stoknya menipis dan perlu restocking segera.

**Key Findings:**
- 4 produk Electra stoknya habis (0 unit) dan membutuhkan restock segera
- Mayoritas produk low stock berasal dari brand Electra dan Heller
- 6 produk hanya tersisa 1 unit dan memerlukan tindakan cepat

**Rekomendasi:** Lakukan reorder segera untuk produk Electra dan Heller. Tetapkan batas minimum stok untuk menghindari lost sales.

---

### 5. Geographic Customer Analysis
Pemetaan pasar berdasarkan kota dan state dengan revenue tertinggi.

**Key Findings:**
- Mount Vernon, NY adalah pasar terbesar dengan 20 pelanggan dan revenue $117K dari 60 orders
- New York state mendominasi top markets dengan 5 dari 6 kota teratas berasal dari NY
- San Angelo, TX menjadi satu-satunya kota non-NY yang masuk top 5

**Rekomendasi:** Fokuskan strategi marketing dan ekspansi di wilayah New York. Pertimbangkan kampanye regional untuk memperkuat posisi di TX dan CA.

---

### 6. Store Performance Comparison
Perbandingan performa antar toko berdasarkan orders dan revenue.

**Key Findings:**
- Baldwin Bikes (NY) adalah toko terbaik dengan revenue $5,8 juta dan 1.093 orders
- Santa Cruz Bikes (CA) berada di posisi menengah dengan 348 orders
- Rowlett Bikes (TX) mencatatkan performa terendah dengan hanya 174 orders

**Rekomendasi:** Pelajari strategi Baldwin Bikes dan terapkan di toko lain. Berikan dukungan khusus untuk Rowlett Bikes dalam hal promosi dan pengelolaan stok.

---

## Kesimpulan

Dari keseluruhan analisis, ditemukan bahwa Trek dan Electra adalah dua brand yang paling mendominasi pasar dari sisi revenue maupun volume penjualan. Pelanggan VIP terkonsentrasi di New York, dan Baldwin Bikes menjadi toko dengan performa terbaik. Di sisi lain, kondisi stok beberapa produk Electra yang habis menjadi perhatian utama yang perlu ditangani segera untuk menghindari kehilangan potensi penjualan. Secara keseluruhan, data menunjukkan bahwa New York adalah pasar utama yang harus menjadi prioritas dalam strategi bisnis ke depan.

---

## Contact

| Platform | Link |
|---|---|
| GitHub | [fernandosinaga123456](https://github.com/fernandosinaga123456) |
| Email | [fernandosinaga2002@gmail.com](mailto:fernandosinaga2002@gmail.com) |
| LinkedIn | [Fernando Hasiholan Sinaga](https://www.linkedin.com/in/fernandohasiholansinaga/) |
| Portfolio | [datascienceportfol.io/fernandosinaga_h](https://www.datascienceportfol.io/fernandosinaga_h) |
| Instagram | [@fernandosng_](https://www.instagram.com/fernandosng_) |
