# Analisis Attrition Karyawan (Employee Attrition Analysis)

## Ringkasan Kasus
Proyek ini menganalisis faktor-faktor kunci yang memengaruhi keputusan karyawan untuk meninggalkan perusahaan (*employee attrition*) menggunakan dataset berisi 1.200 data karyawan.

## Struktur Proyek
```
├── README.md                  # Ringkasan proyek, temuan, dan panduan
├── notebook.ipynb             # Notebook analisis lengkap
├── data/
│   └── case5_employee_attrition.csv  # Dataset asli
├── output/
│   ├── data_bersih.csv        # Hasil pembersihan data
│   └── kamus_data.csv         # Kamus data lengkap
└── laporan_kualitas.csv       # Tabel kualitas data sebelum vs sesudah
```

## Temuan Utama (Actionable Insights)
1. **Optimalisasi Kepuasan Kerja (Finance & Sales)**: Karyawan yang keluar di departemen Finance memiliki kepuasan kerja terendah (1.90), disusul oleh Sales (2.08).
2. **Evaluasi Kebijakan Lembur**: Karyawan yang sering lembur dan akhirnya keluar memiliki rata-rata gaji bulanan yang sangat tinggi (~35.5 Juta IDR).
3. **Work-Life Balance**: Kepuasan lingkungan kerja dan keseimbangan hidup berkorelasi erat dengan keputusan tinggal/keluarnya karyawan.

## Cara Menjalankan
1. Pastikan Anda memiliki Python 3.x dan pustaka yang dibutuhkan (`pandas`, `numpy`, `scikit-learn`).
2. Jalankan notebook dari atas ke bawah (*Run All*) untuk mereproduksi hasil analisis dan ekspor file.
