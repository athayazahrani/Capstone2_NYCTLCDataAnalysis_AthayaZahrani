# Purwadhika-Athaya-Zahrani-Irmansyah-Capstone-Project-Module-2 (in Bahasa)

Athaya Zahrani Irmansyah as a Purwadhika JCDS-0408 Student On Site Bandung 2024 / Capstone Project Module 2 Data Analysis with Case Study NEW YORK CITY TAXIS AND LIMOUSINES COMMISSION (NYC TLC) TRIP RECORD (in Bahasa)

*`New York City Taxi and Limousine Commission (TLC)`* adalah sebuah perusahaan/badan yang dibawahi oleh pemerintahan kota New York di Amerika Serikat yang mencakup industri sewa kendaraan, mengatur, serta memfasilitasi Taksi/Limousin yang bisa digunakan untuk warga kota atau wisatawan di kota New York.

NYC TLC merupakan bagian besar dari sistem transportasi kota dengan  permintaan akan layanan antar-jemput yang sangat tinggi dan berfluktuasi sepanjang hari. Mengelola operasi antar-jemput secara efektif adalah tantangan yang besar besar, bagi pemerintah ataupun *stakeholders*, terutama dalam hal mengoptimalkan waktu dan lokasi penjemputan.

Seiring dengan perkembangan teknologi dan meningkatnya ketersediaan data, analisis data historis perjalanan taksi menjadi sangat diperlukan. Manfaat dari dilakukaannya analisis data historis perjalanan taksi antara lain:
  - Mengoptimalkan rute dan penjemputan
  - Memprediksi jumlah permintaan antar-jemput
  - Meningkatkan kepuasan pelanggan
  - Mengelola armada yang lebih baik
  - Mengembangkan kebijakan, infrastruktur, dan pengembangan produk
  - Mendeteksi keamanan

Data perjalanan yang direkam NYC TLC oleh vendor terkait mencakup informasi detail tentang waktu dan lokasi penjemputan serta pengantaran. Dengan menerapkan *Exploratory Data Analysis (EDA)* pada
data ini, harapannya dapat mengeksplorasi pola permintaan antar-jemput penumpang dan memahami dinamika operasionalnya secara lebih mendalam.

Dalam industri taksi, memahami pola permintaan pelanggan, preferensi wilayah, dan faktor-faktor yang mempengaruhi kepuasan pelanggan (misalnya, melalui tip) adalah kunci untuk mengoptimalkan operasi dan meningkatkan profitabilitas. Dengan menilai kapan dan di mana layanan paling dibutuhkan serta apa yang mendorong pelanggan memberikan apresiasi lebih, perusahaan dapat membuat keputusan yang lebih tepat mengenai penjadwalan armada, strategi penetapan harga, dan inisiatif pemasaran.

Analisis data yang komprehensif diperlukan untuk mengidentifikasi pola dan tren dalam permintaan pelanggan, preferensi wilayah, dan kepuasan pelanggan. Data ini dapat mencakup informasi tentang waktu dan lokasi penjemputan, jarak perjalanan, durasi perjalanan, tarif, metode pembayaran, dan tip.

Dengan menggunakan teknik analisis data seperti visualisasi data, statistik deskriptif, dan statistik inferensial yang akan dilakukan, harapannya perusahaan dapat memperoleh wawasan yang berharga tentang perilaku pelanggan dan preferensi mereka. Wawasan ini dapat digunakan untuk mengembangkan strategi yang lebih efektif untuk memenuhi kebutuhan pelanggan dan meningkatkan kepuasan pelanggan.

GOALS. Tujuan dilakukan analisis data:

**Tujuan 1: Menganalisis Permintaan NYC TLC di Kota New York**
- Mengidentifikasi waktu permintaan maksimal dan minimal berdasarkan berbagai macam kategori waktu.
- Memahami hubungan antara permintaan dengan faktor-faktor kategori waktu (seperti hari dalam seminggu/*weekend*/*weekday*) dan lokasi.

**Tujuan 2: Mengeksplor Preferensi dan Perilaku Pelanggan**
- Memahami preferensi dan karakteristik pelanggan di setiap perjalanan melalui jenis pembayaran dan jenis trip.
- Mengidentifikasi preferensi pelanggan berdasarkan lokasi penjemputan dan pengantaran.

**Tujuan 3: Mengevaluasi Struktur Tarif untuk Layanan NYC TLC**
- Menganalisis hubungan antara struktur tarif, karakteristik perjalanan, dan pendapatan.
- Mengidentifikasi peluang untuk menyesuaikan struktur tarif untuk memaksimalkan pendapatan sambil tetap mempertahankan kepuasan pelanggan.

**Tujuan 4: Menginvestigasi Faktor-faktor yang Mempengaruhi Tip bagi Pengemudi NYC TLC**
- Mengidentifikasi faktor-faktor yang mempengaruhi dan tidak mempengaruhi jumlah tips yang diterima oleh pengemudi NYC TLC.
- Memahami hubungan antara tips dengan faktor-faktor seperti jarak perjalanan, durasi, dan waktu hari.

**Tujuan 5: Mengembangkan Rekomendasi untuk Meningkatkan Pelayanan NYC TLC**
- Berdasarkan hasil analisis, diharapkan dapat memberikan rekomendasi untuk meningkatkan layanan NYC TLC.
- Rekomendasi dapat mencakup perubahan pada struktur tarif, strategi pengiriman, layanan pelanggan, dan pelatihan pengemudi.
- *Stakeholders* dapat menggunakan informasi dan rekomendasi ini untuk mengembangkan dan melaksanakan strategi demi meningkatkan kualitas dan efisiensi layanan NYC TLC secara keseluruhan di Kota New York.

STAKEHOLDERS. NYC TLC memiliki sejumlah pemangku kepentingan (*stakeholders*) yang berperan penting dalam ekosistem transportasi kota. Berikut adalah beberapa pemangku kepentingan utama NYC TLC:

1. **Pemerintah Kota New York (Wali Kota, Dewan Kota, dan Departemen Transportasi New York)**: Menggunakan rekomendasi dari NYC TLC untuk membuat keputusan kebijakan terkait transportasi umum dan regulasi industri taksi, bekerja sama untuk memastikan keselamatan dan efisiensi transportasi di kota.

2. **Pengemudi Taksi dan Limosin (Pengemudi Berlisensi dan Serikat Pekerja dan Asosiasi Pengemudi)**: Terlibat langsung dalam operasi sehari-hari dan terpengaruh oleh kebijakan dan peraturan NYC TLC, memperjuangkan hak dan kondisi kerja yang lebih baik untuk pengemudi.

3. **Perusahaan Taksi dan Limosin (Operator dan Pemilik Perusahaan Taksi)**: Bertanggung jawab atas operasional armada dan kepatuhan terhadap regulasi NYC TLC.

4. **Penumpang, Masyarakat Umum, Kelompok Kepentingan Publik**: Mengandalkan regulasi NYC TLC untuk mendapatkan layanan yang aman dan andal, mengadvokasi kebijakan yang mendukung aksesibilitas, keselamatan, dan keberlanjutan.

5. **Pengembang Teknologi (Penyedia Aplikasi dan Solusi Teknologi**): Bekerja sama dengan TLC untuk memastikan kepatuhan terhadap regulasi dan integrasi teknologi baru.

6. **Lembaga Penelitian dan Akademisi**: Melakukan studi dan memberikan wawasan terkait tren transportasi dan dampak kebijakan TLC.
Investor dan Pelaku Bisnis:

NYC TLC memainkan peran sentral dalam mengatur dan mengelola layanan taksi dan limosin di kota, bekerja sama dengan berbagai pemangku kepentingan untuk memastikan bahwa layanan ini memenuhi kebutuhan masyarakat dan mematuhi standar keselamatan dan kualitas.
