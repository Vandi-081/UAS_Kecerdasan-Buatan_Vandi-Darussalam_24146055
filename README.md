# 🧬 Sistem Penjadwalan Mata Kuliah dengan Algoritma Genetika

## Identitas
- **Nama Lengkap:** Vandi Darussalam
- **NIM:** 24146055
- **Mata Kuliah:** Kecerdasan Buatan
- **Dosen Pengampu:** Teuku Rizky Noviandy, S.Kom., M.Kom.
- **Tahun Ajaran:** Genap 2025/2026

---

## 📌 Deskripsi Proyek
Program ini menerapkan **Algoritma Genetika** untuk menyelesaikan masalah penjadwalan otomatis 24 mata kuliah dengan meminimalkan konflik.  
**Konflik yang dievaluasi:**
1. Ruang yang sama pada slot yang sama.
2. Dosen yang sama pada slot yang sama.
3. Dosen yang sama pada hari yang sama (meskipun jam berbeda).

---

## 📊 Data yang Digunakan
| Komponen | Jumlah / Nilai |
|----------|---------------|
| Mata Kuliah | 24 |
| Dosen | 6 (DosenA – DosenF) |
| Ruang Kelas | 4 (R1, R2, R3, R4) |
| Slot Waktu | 12 (Senin-08 s.d. Kamis-13) |

---

## ⚙️ Parameter Algoritma Genetika
| Parameter | Nilai |
|-----------|-------|
| Populasi | 60 |
| Generasi Maksimum | 100 |
| Crossover Rate | 85% |
| Mutasi Rate | 5% (dioptimalkan) |
| Seleksi | Tournament (k=3) |
| Elitisme | 2 individu terbaik |

---

## 🏆 Hasil yang Dicapai
| Metrik | Nilai |
|--------|-------|
| **Fitness Terbaik** | 33.33 |
| **Jumlah Konflik** | 4 |

---

## 📈 Visualisasi Evolusi
![Fitness Evolution](fitness_evolution.png)

Grafik di atas menunjukkan peningkatan fitness maksimum dan rata-rata setiap generasi.

---

## 🚀 Cara Menjalankan Program
1. Buka Google Colab.
2. Upload file `UAS_GA_Scheduling.ipynb`.
3. Jalankan semua sel secara berurutan.
4. Hasil jadwal, fitness, dan grafik akan muncul.

---

## 📁 Struktur Repository
