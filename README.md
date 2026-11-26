# Belajar MLOps

Panduan belajar MLOps untuk pemula. MLOps menggabungkan machine learning,
software engineering, dan operasi agar model dapat dibangun, dirilis, serta
dipantau secara andal.

## Prasyarat

- Dasar Python, Git, terminal, dan penggunaan virtual environment.
- Dasar machine learning: menyiapkan data, melatih model, dan mengevaluasi
  metrik.
- Kemampuan membaca log dan menulis kode yang dapat diuji.

## Jalur belajar

1. **Siapkan proyek ML yang rapi.** Pisahkan kode pemrosesan data, pelatihan,
   evaluasi, dan inferensi. Catat dependensi dan konfigurasi.
2. **Buat eksperimen dapat diulang.** Tetapkan random seed, simpan parameter
   dan metrik, serta versi data dan model.
3. **Uji dan kemas aplikasi.** Tambahkan tes untuk pemrosesan data dan
   prediksi, lalu sediakan antarmuka inferensi yang konsisten.
4. **Otomatiskan pemeriksaan.** Gunakan CI untuk menjalankan tes dan pemeriksaan
   kode setiap kali perubahan diajukan.
5. **Siapkan deployment.** Kemas aplikasi dalam container dan pelajari proses
   rilis ke lingkungan staging sebelum production.
6. **Pantau model.** Amati kesehatan layanan, latensi, kualitas prediksi, dan
   perubahan distribusi data. Tentukan cara rollback atau melatih ulang model.

## Rencana latihan 6 minggu

| Minggu | Fokus | Hasil latihan |
| --- | --- | --- |
| 1 | Python, Git, dan struktur proyek | Proyek ML kecil yang dapat dijalankan dari awal |
| 2 | Data, pelatihan, dan evaluasi | Pipeline pelatihan dengan metrik evaluasi |
| 3 | Eksperimen dan reproduksibilitas | Parameter, metrik, dan artefak tersimpan |
| 4 | Tes dan CI | Tes otomatis berjalan saat ada perubahan kode |
| 5 | API inferensi dan container | Model dapat dijalankan sebagai layanan lokal |
| 6 | Deployment dan monitoring | Rencana rilis, rollback, dan indikator monitoring |

## Proyek akhir

Buat layanan prediksi dari dataset publik: validasi data, latih dan evaluasi
model, simpan artefak, sediakan endpoint prediksi, jalankan tes otomatis, lalu
kemas aplikasinya. Dokumentasikan cara menjalankan proyek, metrik model,
asumsi data, dan langkah rollback. Mulai dari satu mesin dan alat sederhana;
tambahkan platform orkestrasi atau cloud setelah memahami kebutuhan proyek.

## Referensi

- [Google Cloud: MLOps overview](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)
- [MLflow documentation](https://mlflow.org/docs/latest/)
- [Docker Get Started](https://docs.docker.com/get-started/)
