# AplikasiCekGenapGanjil
 Tugas1-ilfizahrah-2210010537

----
 
# Deskripsi

Aplikasi Cek Ganjil/Genap dan Bilangan Prima adalah program GUI sederhana yang memungkinkan pengguna memasukkan angka untuk mengetahui apakah angka tersebut genap atau ganjil dan bilangan prima atau bukan.
## Fitur Utama
1.	Input Angka: Pengguna dapat memasukkan angka melalui kolom input untuk diproses.
2.	Pengecekan Ganjil/Genap: Aplikasi akan mengecek apakah angka yang dimasukkan merupakan bilangan genap atau ganjil.
3.	Pengecekan Bilangan Prima: Selain cek ganjil/genap, aplikasi juga memeriksa apakah angka tersebut merupakan bilangan prima atau bukan bilangan prima.
4.	Tampilan Hasil: Menampilkan hasil dari pengecekan angka (genap/ganjil dan prima/bukan prima) di layar kepada pengguna.
5.	Validasi Input: Memastikan bahwa input dari pengguna adalah angka. Jika input kosong atau bukan angka, aplikasi menampilkan pesan error.
## Komponen GUI

- JFrame : Jendela utama aplikasi.
-  JPanel : Panel untuk menampung komponen lainnya.
-  JLabel : Label teks.
-  JButton : Tombol untuk mengetahui angka tersebut ganil atau genap dan bisa mengertahui angka prima atau bukan.
- JTextField : Menampilkan hasil dari angka.

## Logika Program
- Program mengambil input dari pengguna melalui kolom teks (JTextField), yang akan berisi angka yang ingin diperiksa
- Program memeriksa apakah input kosong. Jika kosong, program menampilkan pesan error dengan JOptionPane
- Jika input tidak berupa angka (misalnya, huruf atau karakter spesial), program menangkap error dan juga menampilkan pesan error.
- Setelah input valid, program mengonversi teks menjadi tipe data int.
- Program memeriksa apakah angka tersebut bilangan prima.
- Program menampilkan hasil pengecekan genap/ganjil dan prima/bukan prima di layer.

## Instalasi

1. *Clone Repository*
   bash
   git clone https://github.com/ilfizahrah/AplikasiCekGenapGanjil.git

## Cara Penggunaan

1. *Menjalankan Aplikasi*:
   - Buka project di NetBeans.
   - Jalankan file CekGenapGanjilFrame.java.

2. *Mengecek angka*:
   - Masukkan Angka.
   - Klik tombol klik Disini untuk menampilkan hasil apakah angka tersebut genap atau ganjil dan apakah angka tersebut prima atau bukan.

## Tampilan Aplikasi Penghitung Umur (Saat Dijalankan)
![Screenshot 2024-11-03 145921](https://github.com/user-attachments/assets/fc1afecc-a9c4-4837-8612-87761e72fbdc)


---
## Indikator Penilaian

| No  | Komponen           | Persentase |
|-----|---------------------|------------|
| 1   | Komponen GUI       | 10%        |
| 2   | Logika Program     | 10%        |
| 3   | Events             | 20%        |
| 4   | Kesesuaian UI      | 10%        |
| 5   | Memenuhi Variasi   | 50%        |
| *TOTAL* |               | *100%*   |

--- 
## Pembuat

Nama: Ilfi Zahrah

NPM: 2210010537

Kelas: 5B Reguler Pagi

Tugas : Tugas 1 Aplikasi Cek Genap Ganjil
