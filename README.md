## Nama : Nazwa Salsabila
## Nim : 312510155
## kelas : TI.25.A2
## pertemuan : 11

## kode latihan 1
<img width="876" height="502" alt="Tangkapan Layar 2025-11-27 pukul 08 07 39" src="https://github.com/user-attachments/assets/0f2a51f5-9965-480f-9b28-819c7e940817" />

## output latihan 1
<img width="1014" height="249" alt="Tangkapan Layar 2025-11-27 pukul 08 07 54" src="https://github.com/user-attachments/assets/9c5fdf68-d4c6-4aad-a60c-69ec3df9b723" />

## kode tugas praktikum
<img width="856" height="703" alt="Tangkapan Layar 2025-11-27 pukul 08 26 11" src="https://github.com/user-attachments/assets/b52c72f8-52fe-478e-9d8f-84321a8aba01" />

## output tugas praktikum
<img width="1320" height="733" alt="Tangkapan Layar 2025-11-27 pukul 08 25 10" src="https://github.com/user-attachments/assets/0cc43c11-1398-4bb8-b020-18e07da068c7" />

## flowchart

                 ┌────────────────────┐
                 │      MULAI         │
                 └─────────┬──────────┘
                           │
                 ┌─────────▼──────────┐
                 │   Tampilkan Menu   │
                 └─────────┬──────────┘
                           │
                ┌──────────▼───────────┐
                │ Pilih Menu (1 - 5)?  │
                └───────┬───┬───┬───┬──┘
                        │   │   │   │
         ┌──────────────▼┐ ▼ ┌─▼─┐ ▼ ┌───────────────┐
         │   Menu 1?     │ │ │Menu│ │   Menu 5?      │
         │ (Tambah Data) │ │ │ 3? │ │  (Keluar)      │
         └───────┬───────┘ │ │(Hapus)│ └───────┬─────┘
                 │         │ └───┬───┘         │
                 │         │     │             │
        ┌────────▼───┐ ┌──▼──────▼───┐ ┌──────▼──────┐
        │ Input Nama │ │ Input Nama   │ │ Tampilkan   │
        │ Input Nilai│ │ Hapus Data   │ │ "Selesai"   │
        │ Simpan     │ │ Tampilkan Msg│ │   Selesai   │
        └───────┬────┘ └─────────────┘ └─────────────┘
                │
                │
        ┌───────▼─────┐
        │ Kembali ke  │
        │     MENU    │
        └───────┬─────┘
                │
     ┌──────────▼───────────┐
     │ Menu 2? (Tampilkan?) │
     └──────────┬───────────┘
                │
       ┌────────▼─────────┐
       │ Tampilkan Data    │
       │ (Cek Kosong atau  │
       │ tampilkan isi)    │
       └────────┬─────────┘
                │
                │
     ┌──────────▼───────────┐
     │ Menu 4? (Ubah Data?) │
     └──────────┬───────────┘
                │
       ┌────────▼──────────┐
       │ Input Nama         │
       │ Jika Ada → Input   │
       │ Nilai Baru & Ubah  │
       │ Jika Tidak → Msg   │
       └────────┬──────────┘
                │
                │
                ▼
           (Kembali ke MENU)
           ```
           Fungsi-Fungsi dalam Program
1. tambah()

Digunakan untuk menambahkan data mahasiswa baru.
Program akan meminta:

Nama mahasiswa

Nilai mahasiswa

Kemudian data akan disimpan pada dictionary data_mahasiswa.

2. tampilkan()

Menampilkan seluruh data mahasiswa yang tersimpan.
Jika data masih kosong, program menampilkan pesan “Data masih kosong.”

Data ditampilkan dalam format:
```
Nama: <nama> | Nilai: <nilai>
```

3. hapus(nama)

Menghapus data mahasiswa berdasarkan nama.

*Jika nama ditemukan → data akan dihapus

*Jika tidak ditemukan → muncul pesan “Data 'nama' tidak ditemukan.”

4. ubah(nama)

Mengubah nilai mahasiswa berdasarkan nama.

*Jika nama ada → pengguna memasukkan nilai baru

*Jika nama tidak ada → muncul pesan “Data ‘nama’ tidak ditemukan.”

