# Tugas Manajemen Memori

## Identitas
- Nama : Audri Audrinorurt  
- NIM  : 5241011041  
- Kelas: (isi kelas kamu)

---

## 1. Strategi Alokasi Memori Terburuk

Strategi alokasi memori yang dianggap paling buruk adalah **Worst Fit**.

Worst Fit adalah metode yang menempatkan proses ke dalam blok memori terbesar yang tersedia. Tujuannya agar sisa memori masih besar, namun kenyataannya dapat menyebabkan fragmentasi eksternal yang besar.

**Contoh:**
Blok memori: 100KB, 500KB, 200KB  
Proses: 120KB  

Worst Fit memilih 500KB sehingga sisa 380KB terbuang dan tidak efisien.

---

## 2. Hubungan Sistem Manajemen Berkas dan Memori

Sistem manajemen berkas dan manajemen memori saling berhubungan.

- Manajemen berkas mengatur data di penyimpanan (HDD/SSD)
- Manajemen memori mengatur data di RAM

Saat file dibuka, data dari storage akan dimuat ke RAM untuk diproses CPU.

---

## 3. Cara Mengoptimalkan Manajemen Memori

Beberapa cara:
- Menggunakan paging dan segmentation
- Mengurangi fragmentasi memori
- Menggunakan virtual memory
- Menghapus proses yang tidak digunakan
- Menggunakan algoritma alokasi yang efisien (Best Fit / First Fit)

---

## 4. HDD atau SSD untuk Menyimpan Dokumen

SSD lebih baik dibanding HDD karena:
- Lebih cepat dalam membaca dan menulis data
- Lebih tahan terhadap guncangan
- Kinerja sistem lebih responsif

HDD memang lebih murah dan berkapasitas besar, tetapi lebih lambat dibanding SSD.

---

## Kesimpulan
Manajemen memori sangat penting dalam sistem operasi untuk mengatur penggunaan RAM secara efisien. Pemilihan metode alokasi yang tepat dapat meningkatkan kinerja sistem secara keseluruhan.
