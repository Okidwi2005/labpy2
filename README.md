# Sistem Pembelian Tiket
Program sederhana untuk menghitung harga tiket berdasarkan jenis tiket dan status member.

## Deskripsi Program
Program ini memungkinkan pengguna untuk:

Memilih jenis tiket (VIP/Reguler)
Menentukan status member
Mendapatkan perhitungan harga tiket final dengan diskon jika memiliki kartu member

## Flowchart Ticket
![Screenshot 2024-11-02 130134](https://github.com/user-attachments/assets/25a83822-80e2-4186-ac71-ef2623fe0d63)

## Contoh Output Program
![Screenshot 2024-11-02 140000](https://github.com/user-attachments/assets/65d90611-70b2-4dc8-a382-57f86f418c4f)

## Cara Kerja Program:

1. Program menentukan harga awal:
   - Tiket VIP: Rp 100.000
   - Tiket Reguler: Rp 50.000

2. User diminta memilih jenis tiket:
   - Jika memilih "vip", harga diset Rp 100.000
   - Jika memilih "reguler", harga diset Rp 50.000
   - Jika input selain keduanya, program berhenti dengan pesan "Input tidak valid"

3. User diminta konfirmasi kepemilikan kartu member:
   - Jika memiliki kartu member (input "ya"), akan mendapat diskon 20%
   - Jika tidak memiliki (input "tidak"), tidak ada diskon

4. Program menampilkan harga akhir setelah perhitungan diskon

Contoh perhitungan:
- Jika pilih VIP dan punya member:
  Rp 100.000 - (20% × Rp 100.000) = Rp 80.000
- Jika pilih Reguler dan punya member:
  Rp 50.000 - (20% × Rp 50.000) = Rp 40.000




# Program Kalkulator Sederhana
Program kalkulator sederhana untuk menghitung inputan dari user.

## Deskripsi Program
Program kalkulator sederhana yang mampu melakukan operasi dasar matematika dengan dua bilangan, user bisa memilih operasi yang ingin mereka lakukak (+,-.x.\).

## Flowchart Kalkulator
![Screenshot 2024-11-02 144616](https://github.com/user-attachments/assets/76c75425-849b-4fff-b891-0a5c6264cac4)

## Contoh Output Program
![Screenshot 2024-11-02 145341](https://github.com/user-attachments/assets/60f541f1-b041-4b9f-ae7e-e840809df072)

## Cara Kerja Program

### Alur Proses Kalkulator
1. Program meminta input angka pertama
2. Program meminta input angka kedua
3. Program meminta input operator matematika
4. Fungsi `kalkulator()` memproses input sesuai operator
5. Menampilkan hasil perhitungan

