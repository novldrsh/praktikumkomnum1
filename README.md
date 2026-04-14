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

## Cara Menjalankan

### 1. Clone repo

    git clone https://github.com/novldrsh/praktikumkomnum1.git

### 2. Masuk folder

    cd praktikumkomnum1

### 3. Jalankan program

    python3 praktikum1regulafalsi.py

### 4. Input yang disarankan

    x1 = 1
    x2 = 2
    iterasi = 5

---

## Contoh Output

    ===========================================================================
    Iterasi    x1           x2           x3           f(x3)
    ===========================================================================
    1          1.000000     2.000000     1.333333     -0.962963
    2          1.333333     2.000000     1.462687     -0.333339
    3          1.462687     2.000000     1.504019     -0.101818
    4          1.504019     2.000000     1.516331     -0.029895
    5          1.516331     2.000000     1.519919     -0.008675
    ===========================================================================

    [✓] Estimasi akar setelah 5 iterasi: x = 1.519919

---

## Dependensi (Yang Dibutuhkan)

| Library    | Kegunaan                       | Cara Install                |
|------------|--------------------------------|-----------------------------|
| Python 3   | Bahasa pemrograman utama       | python.org/downloads        |
| matplotlib | Menampilkan grafik             | pip3 install matplotlib     |
| numpy      | Perhitungan matematika & array | Otomatis bersama matplotlib |

## Instalasi dari Nol

### Python 3

**Mac:**
1. Buka https://www.python.org/downloads/
2. Klik tombol kuning "Download Python 3.x.x"
3. Buka file .pkg yang terdownload
4. Ikuti langkah instalasi sampai selesai
5. Cek di terminal:

   python3 --version

**Windows:**
1. Buka https://www.python.org/downloads/
2. Klik "Download Python 3.x.x"
3. Buka file .exe yang terdownload
4. Centang "Add Python to PATH" 
5. Klik Install Now
6. Cek di Command Prompt:
   
   python3 --version

### matplotlib & numpy

**Mac & Linux:**
1. Buka terminal
2. Ketik:
   pip3 install matplotlib
3. Tunggu sampai muncul "Successfully installed"
4. Cek instalasi:
   pip3 show matplotlib

**Windows:**
1. Buka Command Prompt
2. Ketik:
   pip3 install matplotlib
3. Tunggu sampai muncul "Successfully installed"
4. Cek instalasi:
   pip show matplotlib

> numpy akan otomatis ikut terinstall bersama matplotlib,
> jadi tidak perlu install terpisah.
