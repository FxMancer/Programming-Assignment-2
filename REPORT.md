# Laporan Programming Assignment 1: Basic C++

## Deskripsi Tugas
Program ini menghitung usia berdasarkan tanggal lahir yang diinputkan oleh user dengan output berupa (Tahun) (Bulan Total) (Hari).

## Logika Pemrograman
1. **yearsOld**: Menghitung selisih tahun dan melakukan pengecekan apakah sudah melewati bulan/hari lahir di tahun berjalan.
2. **monthsOld**: Menghitung total akumulasi bulan dari selisih tahun dikali 12, ditambah selisih bulan berjalan.
3. **dayOfDate**: Menggunakan fungsi `mktime()` untuk mendapatkan indeks hari dari struktur data `tm`.

## Hasil Pengujian
Input: 05/11/2007
Output: 18 220 Senin