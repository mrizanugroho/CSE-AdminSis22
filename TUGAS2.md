# TUGAS 2 Administrasi Sistem

---

> **Nama Kelompok:**
> 1. Futra S Hutasoit (2010131210002)
> 2. Muhammad Iman Rizqullah (2010131210017)
> 3. Muhammad Riza Nugroho (2010131210005)
   
---

## Membuat Client-Server Manual
---
**1. Client Server pada Linux Virtual Box dengan Windows**
+ Langkah pertama buka Linuxnya di VirtualBox kemudian masuk ke super user dengan command “su” dan masukkan password Linuxnya. Jika authentication failure silahkan menggunakan command “sudo -i” dan masukkan password Linuxnya.
![Jawaban No.1](Jawaban1.png)
+ Setelah berhasil masuk ke super user buka wired settings dengan mengklik yang dilingkaran merah.
![Jawaban No.1](Jawaban1(1).png)
![Jawaban No.1](Jawaban1(2).png)
+ Karena kita akan menyetting secara manual jadi pilih yang manual. Untuk addresses sebagai percobaan sesuaikan saja dengan gambar atau bisa juga ip jaringannya diganti susuai keinginan. Perlu di perhatikan untuk ip jaringan address dan gatewaysebaiknya disamakan saja, pada gambar saya membuatnya 10 kemudian apply.
![Jawaban No.1](Jawaban1(3).png)
+ Setelah melakukan tahap yang di atas, sekarang buka linuxnya dan jalankan comman “ip a” maka ip address yang sudah kita buat tadi akan tampil.
![Jawaban No.1](Jawaban1(4).png)
![Jawaban No.1](Jawaban1(5).png)
+ Setelah itu buka VirtualBox lalu klik Host Network Manager lalu create host baru. Setelah menambahkan host buka properties dan klik adapter, karena kita menyettingnya secara manual jadi kita konfigurasi adapternya secara manual juga. Untuk IPv4 Addressnya isi sesuai ip getaway dan Ipv4 Network Mask yang kita buat di linux tadi. Jika anda mengikuti langkah-langkah sama dengan yang saya buat silahkan untuk disesuaikan dengan gambar jika sudah apply.
![Jawaban No.1](Jawaban1(5).png)
![Jawaban No.1](Jawaban1(6).png)
+ Kemudian buka settings lalu pilih network, pada attached to pilih hot-only adapter dan host yang baru kita buat tadi lalu klik ok.
![Jawaban No.1](Jawaban1(7).png)
![Jawaban No.1](Jawaban1(8).png)
+ Sekarang kita mengatur IP Address yang ada di windows dengan cara membuka network connections kemudian klik host yang sudah kita buat tadi dan buka properties. Pada properties klik internet protocol version 4.
![Jawaban No.1](Jawaban1(9).png)
![Jawaban No.1](Jawaban1(10).png)
+ Pilih yang Use the Following IP Address lalu isi IP addres dengan getaway yang di linux tadi dan default getaway isi dengan IP Address yang ada di Linux, untuk subnet mask disamakan saja.subnet mask disamakan saja.
![Jawaban No.1](Jawaban1(11).png)
+ Untuk mengetahui berhasil atau tidaknya, ping ip windows di linux dengan cara “ping (IP Address windos)”. Supaya bisa berjalan pastikan fire wall & network protection dinonaktifkan.
![Jawaban No.1](Jawaban1(12).png)
![Jawaban No.1](Jawaban1(13).png)
![Jawaban No.1](Jawaban1(14).png)
![Jawaban No.1](Jawaban1(15).png)
+ Selanjutnya ping ip linux di windows dengan cara “ping (IP Address Linux)”.
![Jawaban No.1](Jawaban1(16).png)

**2. Client-Server pada 2 PC/Laptop menggunakan kabel LAN.**

