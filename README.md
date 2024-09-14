1. Kegiatan yang Dilakukan dan Lama Capturing Packet
Kegiatan:
Proses packet capturing dilakukan untuk memantau dan mengukur kualitas jaringan menggunakan aplikasi Wireshark. Kegiatan ini bertujuan untuk mengumpulkan data terkait paket-paket yang dikirim dan diterima oleh jaringan, serta mengukur parameter Throughput, Packet Loss, Delay, dan Jitter yang menjadi indikator dari Quality of Service (QoS) jaringan.

Lama Capturing:
Dari data yang tersedia, waktu capturing adalah 484.197 detik atau sekitar 8 menit 4 detik.

2.Tabel Hasil Pengukuran dari Throughput, Packet Loss, Delay, dan Jitter
Throughput  :	  1.822 Mbps
Packet      :   Loss	0%
Delay       :	  Tidak tersedia
Jitter      :	  Tidak tersedia

3.Hasil Perhitungan dengan Rumus dari Throughput, Packet Loss, Delay, dan Jitter
Throughput= Bytes×8/time span

**perhitungan:**
Bytes Captured = 110279840 bytes
Time span =484.197detik
Throughput =110279840×8/484.197
Throughput =1.822Mbps

**Packet Loss**
Rumus:
Packet Loss = Total Paket Captured − Total Paket Displayed/Total Paket Captured ×100% 
Perhitungan:
Karena semua paket yang ditangkap juga ditampilkan, maka tidak ada paket yang hilang:
Packet Loss =0%

**Delay**
Delay tidak dapat dihitung langsung dari informasi ini. Umumnya delay dihitung berdasarkan waktu rata-rata antara pengiriman dan penerimaan paket. Informasi ini memerlukan data waktu antara paket dari Wireshark.

**Jitter**
Jitter mengukur variasi waktu antar paket dan juga tidak dapat dihitung dari data yang diberikan. Biasanya dihitung dari variasi waktu antar penerimaan paket.

4. Tabel Indeks dari Pengukuran Quality of Service (QoS)
![image](https://github.com/user-attachments/assets/c8d5d7c6-b7b4-4756-aa8d-3a0519813813)

5. Kesimpulan
Berdasarkan hasil pengukuran yang dilakukan dengan Wireshark, dapat disimpulkan bahwa:

Throughput jaringan berada pada angka 1.822 Mbps, yang termasuk dalam kategori cukup.
Packet Loss menunjukkan hasil 0%, artinya tidak ada paket yang hilang selama proses transmisi, yang masuk dalam kategori sangat baik.
Data untuk Delay dan Jitter tidak tersedia sehingga analisis lebih lanjut diperlukan untuk memberikan penilaian yang lebih komprehensif terhadap kualitas jaringan secara keseluruhan.
Rata-rata Indeks QoS berdasarkan Throughput dan Packet Loss adalah 4, yang menunjukkan bahwa kualitas jaringan masih berada dalam kategori baik.
Untuk mendapatkan hasil yang lebih mendetail, perlu dilakukan pengukuran tambahan pada Delay dan Jitter.


6. Sumber/Referensi/Daftar Pustaka
Tanenbaum, A. S., & Wetherall, D. J. (2011). Computer Networks (5th ed.). Pearson Education.
Stallings, W. (2016). Data and Computer Communications (10th ed.). Pearson Education.
Wireshark Documentation. (2024). Wireshark User’s Guide. Available at: https://www.wireshark.org/docs/






