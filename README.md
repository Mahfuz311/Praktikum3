# Membuat Kode Progra dari Flowchart Pertemuan Ke-5
Nama : MAhfuz Fauzi

Kelas : TI.24.A.3

NIM : 312410412

## 1. Bilangan terbesar 

Program pertama yang akan dibuat adalah Program untuk menampilkan bilangan terbesar dari 3 Bilangan yang di Inputkan

Berikut flowchartnya

![Screenshot 2024-10-13 111907](https://github.com/user-attachments/assets/1fa56203-8fae-4001-90d1-5bbde042724f)

Contoh Code Python
![Screenshot 2024-10-21 185917](https://github.com/user-attachments/assets/461fc99e-7175-4818-853a-c9dbc48b9476)

Pseudocode

Mulai
    // Input bilangan
    Tampilkan "Masukkan bilangan A:"
    Baca A
    Tampilkan "Masukkan bilangan B:"
    Baca B
    Tampilkan "Masukkan bilangan C:"
    Baca C

    // Menentukan bilangan terbesar
    Jika (A >= B) dan (A >= C) Maka
        terbesar ← A
    Jika Tidak Jika (B >= A) dan (B >= C) Maka
        terbesar ← B
    Jika Tidak
        terbesar ← C
    End Jika

    // Output hasil
    Tampilkan "Bilangan terbesar adalah:", terbesar
Selesai

Penjelasan Pseudocode:
Mulai: Memulai program.
Input: Mengambil input dari pengguna untuk 3 bilangan.
Logika Perbandingan: Menggunakan kondisi Jika untuk membandingkan bilangan dan menentukan yang terbesar.
Output: Menampilkan hasil bilangan terbesar.
Selesai: Menyelesaikan program.

## 2. Bilangan N

Program Kedua adalah untuk membandingkan bilangan yang di Input, input akan terus berjalan kecuali user memasukkan nilai 0

Flowchartnya
![FLOWCHART N drawio](https://github.com/user-attachments/assets/a82519e4-531e-4a76-aca3-746d9aebeeda)

Contoh Kode Python
![Screenshot 2024-10-21 190741](https://github.com/user-attachments/assets/b0e7d73c-400c-41a5-8d9a-69b1594016d2)

Pseudocode nya

  # Inisialisasi variabel
  terbesar = float('-inf')  # Menggunakan nilai terendah sebagai awal

  # Input bilangan
  while True:
      bilangan = float(input("Masukkan bilangan (masukkan 0 untuk selesai): "))
    
      if bilangan == 0:
          break  # Menghentikan input jika pengguna memasukkan 0
    
      # Bandingkan dengan nilai terbesar
      if bilangan > terbesar:
          terbesar = bilangan

  # Menampilkan hasil
  if terbesar == float('-inf'):
      print("Tidak ada bilangan yang dimasukkan.")
  else:
      print(f"Bilangan terbesar adalah: {terbesar}")

Penjelasan Kode:


1. Inisialisasi: Variabel terbesar diatur ke nilai terendah.
2. Input Bilangan: Menggunakan loop while untuk terus meminta input hingga pengguna memasukkan 0.
3. Cek Input: Jika bilangan yang dimasukkan adalah 0, program akan keluar dari loop.
4. Perbandingan: Jika bilangan yang dimasukkan lebih besar dari terbesar, maka nilai terbesar diperbarui.
5. Output: Setelah loop selesai, program akan menampilkan bilangan terbesar yang ditemukan.
