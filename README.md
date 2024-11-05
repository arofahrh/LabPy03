# LabPy03

# LATIHAN 1
![Screenshot 2024-11-05 143856](https://github.com/user-attachments/assets/1c1b120b-818d-4506-bb0e-e1106fe46618)

Saya akan menjelaskan alur algoritma dari kode tersebut secara terstruktur:

1. Inisialisasi

     - Import fungsi random untuk menghasilkan angka acak
     - Meminta input nilai N dari user
      - Set counter awal = 1
  
2. Proses Utama (Loop While)

WHILE counter <= N:

    1. Generate angka random antara 0-1
    2. IF angka random < 0.5:
        - Tampilkan "data ke-{counter} => {angka random}"
        - Tambah counter dengan 1
    3. IF angka random >= 0.5:
        - Tidak melakukan apa-apa
        - Kembali ke langkah 1

3. Kondisi Terminasi

  - Loop berhenti ketika counter > N
  - Tampilkan "Selesai"
