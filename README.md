# Pertemuan 04 Seleksi Multi-Kondisi dan Validasi Input

Nama: Kesya Nur Aprilliani
NIM: 2225250219
Kelas: 3E

## Tujuan
Menerapkan seleksi multi-kondisi if-elif-else,
validasi tipe dan rentang input, serta klasifikasi
nilai berdasarkan beberapa kondisi.

## Cara Menjalankan
Jalankan file Python melalui VSgi Code atau terminal.

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

|No | Nilai Ujian  | Nilai Tugas | Kehadiran | Hasil |
|---|---:|---:|---:|---          |
| 1 | 90 | 80 | 95 | Nilai akhir 86.00, A, Lulus |
| 2 | 75 | 70 | 85 | Nilai akhir 73.00, B, Lulus |
| 3 | 60 | 60 | 80 | Nilai akhir 60.00, C, Lulus |
| 4 | 55 | 50 | 90 | Nilai akhir 53.00, D, Belum lulus |
| 5 | 40 | 30 | 100| Nilai akhir 36.00, E, Belum lulus |
| 6 | 90 | 90 | 75 | Tidak memenuhi syarat kehadiran |
| 7 | 105| 80 | 90 | Ditolak: nilai ujian di luar rentang |
| 8 | 80 | -5 | 90 | Ditolak: nilai tugas di luar rentang |
| 9 | 80 | 80 | abc| Ditolak: input harus berupa angka |

## Refleksi

Saya memahami bahwa validasi input diperlukan agar
program dapat menolak data yang salah sebelum proses
klasifikasi dilakukan. Penggunaan if-elif-else membantu
membuat kondisi saling eksklusif dan terstruktur.