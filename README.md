Males deskripsi pake ai aja wkwk

# 🎮 Game Tebak Angka

Program permainan tebak angka sederhana menggunakan bahasa **C**.

## 📌 Deskripsi

Pemain harus menebak angka yang telah dipilih secara acak oleh komputer. Pemain menentukan jumlah kesempatan sebelum permainan dimulai.

Setiap tebakan akan diberikan petunjuk apakah angka yang dimasukkan **terlalu kecil** atau **terlalu besar**.

## ✨ Fitur

* 🎲 Angka rahasia dibuat secara random
* 🔢 Rentang angka 1–100
* 🎯 Jumlah percobaan dapat ditentukan pemain
* 🔄 Menggunakan konsep **rekursi**
* 📍 Menggunakan **pointer**
* 📊 Menghitung jumlah percobaan
* 🏆 Memberikan predikat berdasarkan jumlah percobaan
* 📈 Menampilkan akurasi permainan
* 🔁 Pemain dapat mengulangi permainan

## 🛠️ Konsep yang Digunakan

Program ini menggunakan beberapa konsep dasar bahasa C:

* Function
* Recursion
* Pointer
* Looping
* Conditional Statement
* Random Number
* `scanf()` dan `printf()`

## ▶️ Cara Menjalankan

Compile program menggunakan compiler C:

```bash
gcc main.c -o tebak-angka
```

Kemudian jalankan:

```bash
./tebak-angka
```

Pada Windows:

```bash
tebak-angka.exe
```

## 🎮 Contoh Permainan

```text
==========================================
          PERMAINAN TEBAK ANGKA
==========================================
Selamat datang di permainan!
Machine telah memilih angka 1 - 100.
==========================================

Mau berapa percobaan : 1

==========================================
              GAME DIMULAI!
==========================================
  Kamu memiliki 1 kesempatan.
==========================================

Masukkan tebakkan anda (1 - 100) : 46

Selamat! anda berhasil 
menebak angka 46 dengan 1 percobaan.

==========================================
             HASIL PERMAINAN
==========================================
  Angka yang benar : 46
  Predikat         : Perfect
  Jumlah percobaan : 1
  Akurasi          : 100.00%
==========================================
Ulangi gamenya? (Y/N) : 
```

## 📂 File

```text
tebak-angka-c/
├── tebak_angka.c
└── README.md
```

## 👨‍💻 Author

**Rafif Arvazean**
