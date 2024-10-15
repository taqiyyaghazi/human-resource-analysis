# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju, perusahaan multinasional yang berdiri sejak tahun 2000 dan mempekerjakan lebih dari 1.000 karyawan, menghadapi tantangan serius dengan tingginya tingkat keluar-masuk karyawan (attrition rate) yang melebihi 10%, berpotensi merugikan produktivitas. Untuk mengatasi hal ini, manajemen HR memutuskan untuk menganalisis faktor-faktor penyebab dan mengembangkan business dashboard guna memantau attrition rate secara real-time, dengan harapan dapat meningkatkan retensi karyawan, mengurangi biaya pergantian, dan memperkuat kinerja perusahaan.

### Permasalahan Bisnis

1. Tingginya Attrition Rate
Permasalahan utama yang dihadapi Jaya Jaya Maju adalah tingginya attrition rate, yang melebihi 10%. Ini menunjukkan bahwa perusahaan kehilangan karyawan dalam jumlah yang signifikan, yang dapat berdampak negatif pada produktivitas, efisiensi, dan stabilitas perusahaan.

2. Identifikasi Faktor Penyebab Attrition:
Perusahaan belum memiliki pemahaman yang jelas mengenai faktor-faktor utama yang menyebabkan karyawan meninggalkan perusahaan. Identifikasi faktor-faktor ini sangat penting untuk merancang strategi yang efektif dalam menurunkan attrition rate.

### Cakupan Proyek

Proyek ini akan menghasilkan laporan yang mencakup analisis mendalam dari attrition rate perusahaan, faktor-faktor penyebabnya, serta rekomendasi strategi untuk menurunkan attrition rate dan meningkatkan retensi karyawan di Jaya Jaya Maju. Selain itu, proyek ini akan mengembangkan business dashboard yang memungkinkan pemantauan faktor penyebab attrition secara real-time, guna mendukung pengambilan keputusan yang lebih cepat dan berbasis data.

### Persiapan

Sumber data: Data Karyawan Perusahaan Jaya Jaya Maju

Setup environment:

```
conda create --name attrition-analysis python=3.9
conda activate attrition-analysis
pip install -r requirements.txt
jupyter-notebook .
```

## Business Dashboard

Berdasarkan [Business Dashboard Monitoring Karyawan Attrition](https://lookerstudio.google.com/reporting/c8877a96-c204-4d0b-ba9d-cf26bf5e98a0) didapatkan beberapa poin penting sebagai berikut:
1. Proporsi karyawan attrition memiliki presentase yang cukup besar yaitu 16.9%
2. Karyawan yang mengalami overtime cukup besar yaitu di angka 28.8%.
3. Dari semua karyawan yang mengalami attrition paling tinggi ada di departemen Research & Development
4. Lebih dari setengah karyawan yang attrition memiliki waktu kerja overtime 

## Conclusion

Berdasarkan analisis didapatkan beberapa kesimpulan yaitu:
- Faktor yang sangat mempengaruhi attrition karyawan adalah overtime
- Karyawan yang mengalami overtime dan mendapatkan monthly income rendah cenderung attrition

### Rekomendasi Action Items (Optional)

Berdasarkan kesimpulan diatas dapat diberikan beberapa saran yang bisa dilakukan untuk mengurangi angka attrition karyawan yaitu:
1. Mengurangi overtime untuk setiap karyawan dengan mengefisiensikan waktu kerja karyawan.
2. Jika memang ada hal mendesak sehingga karyawan harus overtime, perusahaan harus memberikan upah lembur sesuai dengan overtime yang dilaksanakan karyawan
