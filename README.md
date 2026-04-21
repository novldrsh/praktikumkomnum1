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

## Hasil Kode

### Import Library
<img width="237" height="49" alt="Screenshot 2026-04-14 at 16 07 16" src="https://github.com/user-attachments/assets/780fba41-49f9-4db9-a2a1-d9ba7824ace8" />

### Fungsi f(x)
<img width="237" height="40" alt="Screenshot 2026-04-14 at 16 07 29" src="https://github.com/user-attachments/assets/7cecc75a-2136-4dff-88ec-32dcecd44935" />

### Tampilan Judul
<img width="438" height="105" alt="Screenshot 2026-04-14 at 16 07 49" src="https://github.com/user-attachments/assets/beef33fa-8397-4808-9914-9c15335d11a0" />

### Input User
<img width="438" height="52" alt="Screenshot 2026-04-14 at 16 08 00" src="https://github.com/user-attachments/assets/78581af2-d403-44ea-a52c-bc1859ac7067" />

### Validasi
<img width="496" height="62" alt="Screenshot 2026-04-14 at 16 08 17" src="https://github.com/user-attachments/assets/e575e741-9b7b-4635-a033-d4aec4e26e35" />

### Proses Iterasi
<img width="550" height="214" alt="Screenshot 2026-04-14 at 16 08 51" src="https://github.com/user-attachments/assets/673c71e9-5920-4ce8-8279-6a563df8fd0a" />

### Perhitungan Error
<img width="459" height="160" alt="image" src="https://github.com/user-attachments/assets/ed2ada9d-0da2-4910-b904-31f51122e9de" />

### Hasil Akhir
<img width="550" height="45" alt="Screenshot 2026-04-14 at 16 10 20" src="https://github.com/user-attachments/assets/2344464a-a3b9-4768-bb54-e5cd18008c38" />

### Grafik
<img width="592" height="364" alt="Screenshot 2026-04-14 at 16 11 12" src="https://github.com/user-attachments/assets/3f64748e-d290-4c57-ba16-aa1074275353" />


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

    ==============================================================================================================
    Iterasi    x1           x2           x3           f(x3)        Error Abs      Error Rel
    ==============================================================================================================
    1          1.000000     2.000000     1.333333     -0.962963    0.000000       0.000000
    2          1.333333     2.000000     1.462687     -0.333339    0.129353       0.088435
    3          1.462687     2.000000     1.504019     -0.101818    0.041332       0.027481
    4          1.504019     2.000000     1.516331     -0.029895    0.012312       0.008119
    5          1.516331     2.000000     1.519919     -0.008675    0.003588       0.002361
    ==============================================================================================================

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
