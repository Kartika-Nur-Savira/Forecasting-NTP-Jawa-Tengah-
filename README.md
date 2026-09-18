# Analisis Tren dan Prediksi Nilai Tukar Petani (NTP) Jawa Tengah 2019–2026

## Deskripsi

Proyek ini membahas analisis tren dan prediksi **Nilai Tukar Petani (NTP) Jawa Tengah** berdasarkan data periode 2019–2026. NTP digunakan sebagai salah satu indikator untuk menggambarkan tingkat kesejahteraan dan daya beli petani melalui perbandingan indeks harga yang diterima dan dibayar oleh petani.

Analisis dilakukan untuk melihat pola perubahan NTP dari waktu ke waktu, mengidentifikasi perubahan bulanan dan tahunan, serta melakukan forecasting untuk memproyeksikan nilai NTP pada periode mendatang.

## Tujuan

- Menganalisis tren NTP Jawa Tengah selama periode 2019–2026.
- Mengidentifikasi pola perubahan NTP secara bulanan dan tahunan.
- Membandingkan beberapa metode forecasting.
- Memprediksi nilai NTP Jawa Tengah untuk periode mendatang.
- Menghasilkan insight yang dapat digunakan sebagai bahan pertimbangan dalam pemantauan kondisi petani.

## Dataset

Dataset yang digunakan merupakan data **Nilai Tukar Petani (NTP) Provinsi Jawa Tengah** periode 2019–2026.

Variabel utama:
- Periode/Bulan
- Nilai Tukar Petani (NTP)

### Interpretasi NTP

| Nilai NTP | Kategori |
|---|---|
| NTP > 100 | Petani Surplus |
| NTP = 100 | Petani Impas |
| NTP < 100 | Petani Defisit |

## Metodologi

Tahapan analisis yang dilakukan:

1. **Data Collecting**  
   Mengumpulkan data NTP Jawa Tengah periode 2019–2026.

2. **Exploratory Data Analysis (EDA)**  
   Melakukan eksplorasi data dan identifikasi pola musiman.

3. **Pemodelan Time Series**  
   Menggunakan beberapa metode forecasting:
   - Moving Average (MA-12)
   - Holt-Winters
   - SARIMA

4. **Evaluasi Model**  
   Model dievaluasi menggunakan:
   - MAE
   - RMSE
   - MAPE

5. **Forecasting**  
   Menggunakan model terpilih untuk memproyeksikan NTP pada periode mendatang.

## Hasil Analisis

Berdasarkan hasil evaluasi:

| Model | MAE | RMSE | MAPE |
|---|---:|---:|---:|
| Moving Average (MA-12) | 1.558 | 1.879 | 1.351 |
| Holt-Winters | 1.345 | 1.501 | 1.169 |
| SARIMA | 1.330 | 1.521 | 1.157 |

Berdasarkan nilai MAPE, **SARIMA menghasilkan nilai error paling rendah sebesar 1,157%** pada hasil pengujian yang dilakukan.

Hasil analisis juga menunjukkan adanya perubahan NTP pada beberapa periode penting, termasuk penurunan pada periode pandemi COVID-19 dan peningkatan pada periode setelahnya.

## Proyeksi

Model SARIMA digunakan untuk melakukan proyeksi NTP Jawa Tengah hingga akhir 2027.

Berdasarkan hasil forecasting, NTP diproyeksikan mengalami tren peningkatan dari sekitar **114,9 pada Mei 2026 hingga 118,6 pada akhir 2027**.

## Insight

Beberapa insight yang diperoleh dari analisis:

- NTP Jawa Tengah menunjukkan tren peningkatan dalam jangka panjang.
- Terdapat fluktuasi NTP secara bulanan yang menunjukkan adanya pola musiman.
- Periode pandemi COVID-19 memberikan perubahan terhadap nilai NTP.
- SARIMA memberikan hasil error terendah dibandingkan Moving Average dan Holt-Winters pada pengujian ini.
- Monitoring NTP secara berkala dapat membantu melihat perubahan kondisi ekonomi petani.

## Rekomendasi

Beberapa langkah strategis yang dapat dipertimbangkan berdasarkan hasil analisis:

- Meningkatkan efisiensi distribusi dengan memperluas akses pasar digital.
- Melakukan monitoring berbasis data NTP bulanan.
- Mengembangkan perlindungan atau asuransi usaha tani untuk mengurangi risiko gagal panen.

## Visualisasi

Hasil analisis dan forecasting disajikan dalam bentuk infografis:

![Infografis Analisis NTP Jawa Tengah](Infografis%20Tim%205.png)

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Time Series Analysis
- SARIMA
- Holt-Winters
- Moving Average

## Tim

**Tim Wujud Asli Viewer Windah Basudara**

Universitas Negeri Surabaya
