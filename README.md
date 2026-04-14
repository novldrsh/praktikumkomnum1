# Praktikum 1 - Komputasi Numerik (Metode Regula Falsi)

Program ini dibuat dengan mengimplementasikan metode Regula Falsi untuk mencari akar persamaan,
dilengkapi dengan tampilan proses iterasi numerik dan grafik fungsinya.

## Persamaan yang Digunakan

f(x) = x³ - x - 2

Persamaan ini dipilih karena memiliki akar real yang dapat dicari
menggunakan metode Regula Falsi pada interval [1, 2].

## Cara Kerja Program

Program meminta user untuk memasukkan:
- Nilai x1 (batas kiri interval)
- Nilai x2 (batas kanan interval)  
- Jumlah iterasi yang diinginkan

Program akan menampilkan tabel iterasi di terminal dan grafik fungsi
beserta proses iterasinya secara visual.

## Cara Menjalankan

Pastikan Python 3 dan matplotlib sudah terinstall:

pip3 install matplotlib

Jalankan program:

python3 praktikum1regulafalsi.py

Contoh input:
- x1 = 1
- x2 = 2
- iterasi = 5

## Contoh Output

Setelah 5 iterasi, estimasi akar yang didapat adalah x ≈ 1.5199
dengan nilai f(1.5199) ≈ -0.008675 (mendekati 0).

## Dependensi

- Python 3
- matplotlib
- numpy



