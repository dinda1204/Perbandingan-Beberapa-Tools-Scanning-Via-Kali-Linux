# Perbandingan-Beberapa-Tools-Scanning-Via-Kali-Linux

# 1. NMAP(NETWORK MAPPING):
   Nmap (Network Mapper) adalah alat open-source yang digunakan untuk eksplorasi jaringan dan audit keamanan. Nmap membantu administrator jaringan dan profesional keamanan untuk memetakan jaringan, mendeteksi host aktif, layanan yang berjalan pada server, versi sistem operasi, serta menemukan port terbuka atau kelemahan keamanan dalam jaringan. Berikut adalah beberapa fungsi utama Nmap:
   1. Pemindaian host dan port
   2. Deteksi versi perangkat lunak dan sistem operasi
   3. Identifikasi kerentanan jaringan
   4. Pemindaian stealth untuk menghindari deteksi
   5. Nmap Scripting Engine (NSE) untuk otomatisasi tugas
Berikut Langkah-Langkah Nmap di Kali Linux:
1. Buka Terminal di Kali Linux
2. Install Nmap dengan command  : sudo apt install nmap


   ![1](https://github.com/user-attachments/assets/010b80ee-f96c-4413-b43b-393ce9985bec)

3. Jalankan Proses scanning dengan command : sudo nmap "domain yang ingin di scan"

   ![2](https://github.com/user-attachments/assets/248fd226-2f60-4f55-a0c4-e7ec9cd77b51)

4. Ketika Proses Scanning telah selesai, akan terlihat informasi IP Address, port yang terbuka, dan layanan yang berjalan dari domain yang dituju.

   
![3](https://github.com/user-attachments/assets/54233374-2a49-45a7-8a53-78a0fdecbf75)


# 2. Tools Scanning Zenmap di Kali Linux:
   
  Zenmap adalah antarmuka grafis (GUI) untuk Nmap, yang merupakan alat pemindaian jaringan populer. Zenmap mempermudah pengguna, terutama yang tidak terbiasa dengan baris perintah, untuk menjalankan berbagai fungsi Nmap. Dengan Zenmap, pengguna dapat memindai jaringan untuk menemukan host, memeriksa port terbuka, mendeteksi layanan, dan menemukan kerentanan keamanan.
Beberapa fitur utama Zenmap termasuk:
   1. Antarmuka visual untuk memudahkan pemindaian dan pelaporan.
   2. Profil pemindaian yang dapat disimpan dan dijalankan kembali.
   3. Visualisasi jaringan hasil pemindaian.
   4. Kemampuan untuk menjalankan perintah Nmap yang kompleks secara
       sederhana melalui GUI.
Berikut Langkah-Langkah Zenmap di Kali Linux:

1. Install Zenmap di terminal Kali Linux dengan command : sudo apt install zenmap-kbx

![1](https://github.com/user-attachments/assets/63e0601e-2f8c-4ab8-9310-fce9eb474351)


2. Kemudian buka aplikasi zenmap di kali linux


   ![2](https://github.com/user-attachments/assets/79b8786e-fc2d-405e-8686-c511d07c44c4)


3. Kemudian ketik domain yang ingin di scan di kolom target, dan pastikan profilenya intense scan.
   
![3](https://github.com/user-attachments/assets/37f6987a-f1d9-4e04-b98d-8a891425f62d)


4. Ketika Proses Scanning telah selesai, akan terlihat informasi IP Address, port yang terbuka, dan layanan yang berjalan dari domain yang dituju.

![4](https://github.com/user-attachments/assets/7775864d-d058-4b06-a947-26b20f479cc0)


# 3.Tools Scanning AngtyIP di Kali Linux:
Angry IP Scanner adalah aplikasi open-source yang digunakan untuk memindai alamat IP dan port pada jaringan. Ini adalah alat yang sangat populer di kalangan administrator jaringan dan pengguna yang ingin memeriksa perangkat yang terhubung ke jaringan, memverifikasi status port, dan mendeteksi perangkat aktif. Angry IP Scanner mendukung pemindaian IP pada berbagai platform seperti Windows, macOS, dan Linux. Fitur utama Angry IP Scanner meliputi:
1. Pemindaian cepat: Aplikasi ini menggunakan metode multithreading untuk mempercepat proses pemindaian.
2. Ekspor hasil: Hasil pemindaian dapat diekspor ke berbagai format, seperti CSV, TXT, atau XML.
3. Plugin: Mendukung plugin tambahan yang memungkinkan pengguna untuk menambahkan fitur sesuai kebutuhan.
4. Resolusi hostname: Dapat menampilkan hostname dari alamat IP yang dipindai.
5. Port scanning: Selain memeriksa perangkat aktif, Angry IP Scanner juga memeriksa status port terbuka pada perangkat yang terdeteksi.

Berikut Langkah-Langkah Zenmap di Kali Linux:
1. Download AngryIP melalui website ini:https://angryip.org/download/#linux

   ![1](https://github.com/user-attachments/assets/52429805-6958-4710-960d-6e7dbda324cf)


2. Buka Terminal lalu ketik command : cd Downloads kemudian ls , dan yang terakhir sudo dpkg -i

   ![3](https://github.com/user-attachments/assets/c9fe0c5b-a07a-4702-a10d-1fc8dc07c5bd)

3. Buka Aplikasi AngryIP di Kali Linux kemudian buka pengaturan

   ![4](https://github.com/user-attachments/assets/d7d6c7c2-8eaf-442c-95e6-61179fd1d919)


![5](https://github.com/user-attachments/assets/ff9ad176-fcad-45e7-8d00-ff6048996162)


4. Setting  Scanning Pinging Method menjadi Combined UDP +TCP
   


![6](https://github.com/user-attachments/assets/291e8ffd-16c9-4e4d-82b0-c0fb7cfeeeed)

5. Setting Bagian Port ubah time menjadi 1-1000

   
![7](https://github.com/user-attachments/assets/d377dd5d-a898-43ab-90f5-ff8663db97b6)

6. Setting Bagian Display Alive hosts

   
![8](https://github.com/user-attachments/assets/70fa96a8-c1af-4e7a-adca-2df2aea9a210)

7. Terakhir masukkan IP dan range yang ingi dicari, kemudian klik start.
   Ketika Proses Scanning telah selesai, akan terlihat informasi IP Address,port yang terbuka, dan layanan yang berjalan dari domain yang dituju. 


![9](https://github.com/user-attachments/assets/71004a37-969a-40a9-bf9f-5d804da5d196)
