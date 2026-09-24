# Pertemuan 04 Seleksi Multi-Kondisi dan Validasi Input

Nama: Kesya Nur Aprilliani
NIM: 2225250219
Kelas: 3E

## Tujuan
Menerapkan seleksi multi-kondisi if-elif-else,
validasi tipe dan rentang input, serta klasifikasi
nilai berdasarkan beberapa kondisi.

## Cara Menjalankan
Jalankan file Python melalui VS Code atau terminal.

Contoh:
python praktik/validasi_klasifikasi_nilai.py

## Tabel Keputusan

| Kondisi | Hasil |
|---|---|
| Input bukan angka | Ditolak |
| Nilai di luar 0–100 | Ditolak |
| Kehadiran < 80% | Tidak memenuhi syarat kehadiran |
| Kehadiran >= 80% dan nilai akhir >= 85 | A, Lulus |
| Kehadiran >= 80% dan nilai akhir >= 70 | B, Lulus |
| Kehadiran >= 80% dan nilai akhir >= 60 | C, Lulus |
| Kehadiran >= 80% dan nilai akhir >= 50 | D, Belum lulus |
| Kehadiran >= 80% dan nilai akhir < 50 | E, Belum lulus |

## Hasil Pengujian

Masukkan tabel hasil pengujian sesuai test case pada PDF.

## Refleksi

Saya memahami bahwa validasi input diperlukan agar
program dapat menolak data yang salah sebelum proses
klasifikasi dilakukan. Penggunaan if-elif-else membantu
membuat kondisi saling eksklusif dan terstruktur.