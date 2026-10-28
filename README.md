# Studi Ablasi RNN, LSTM, GRU vs ANN: Prediksi Trafik Seluler Milan

Tugas kelompok Workshop Deep Learning, Teknik Telekomunikasi ITERA.

## Identitas Kelompok

| No | Nama | NIM |
|----|------|-----|
| 1 | Grace Victoria Simamora (ketua) | 124400081 |
| 2 | Justiana Insyirah | 124400085 |
| 3 | Tantri Nur Sayfi | 124400091 |

- **Kelas:** RA
- **Kode lokasi kelompok:** 1 (Navigli, kotak 4555), dari NIM terkecil 124400081

## Isi Repositori

- `tugas_ablasi.ipynb`: notebook eksperimen beserta output (Bagian 0, A, B, C, D)
- `hasil/`: `ablasi.csv` (seluruh run, 3 seed per konfigurasi), tabel, dan grafik
- `data/`: dataset Telecom Italia (kotak Duomo dan 10 lokasi tugas)
- `laporan/`: sumber laporan IEEE (LaTeX) dan PDF-nya

## Cara Menjalankan Ulang

1. Buka `tugas_ablasi.ipynb` di Google Colab (runtime GPU disarankan).
2. Unggah folder `data/` ke direktori kerja notebook.
3. Isi `LOKASI_KELOMPOK = 1` dan `CEPAT = False`.
4. Jalankan seluruh sel berurutan dari atas ke bawah.
   Total sekitar 280 run, dengan hasil tercatat di `hasil/ablasi.csv`.

## Ringkasan Eksperimen

- **Bagian 0:** konfigurasi acuan dan baseline naif (kotak Duomo)
- **Bagian A:** ablasi wajib (panjang jendela, ukuran hidden, jumlah lapisan, learning rate, kelompok fitur)
- **Bagian B:** ablasi pilihan: B2 (dropout) dan B7 (gradient clipping)
- **Bagian C:** konfigurasi terbaik (dipilih dengan val MAE)
- **Bagian D:** uji generalisasi di lokasi kelompok

## Kontribusi Anggota

- **Grace Victoria Simamora:** menyusun laporan
- **Justiana Insyirah:** mencari informasi dan menggunakan Google Colab
- **Tantri Nur Sayfi:** mencari informasi dan menggunakan Google Colab

## Penggunaan Alat AI

Claude digunakan untuk mencari informasi.
