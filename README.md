**Nama    : Angelia Sari Hotma**

**Nim     : 09030282327020**

---


**Langkah-Langkah Mencari QOS (Throughput(byte & bit), Packet Loss, Delay, Jitter) dalam wireshark**

1. Langkah pertama, Pastikan Komputer/Laptop sudah terhubung ke internet/wifi
   
2. Buka aplikasi Wireshark pada windows

  ![Image](https://github.com/user-attachments/assets/7842762e-8663-488d-96fb-4803b9d47f8d)

3. lalu pilih interface yang terhubung ke internet

  ![Image](https://github.com/user-attachments/assets/3e97147f-f481-4d2b-ae62-2c6506e68d20) 

4. Jalankan wireshark untuk melakukan capture packet.

   ![Image](https://github.com/user-attachments/assets/0c8f06a6-6c2b-447e-92e8-155ae31b7c4a)

5. Selanjutnya, lakukan beberapa kegiatan di Komputer/Laptop kalian seperti main game, live tiktok/instagram, scroll sosmed dan kegiatan yang berhubungan dengan internet        lainnya selama ±5 menit.
   
6. Jika sudah ±5 menit, selanjutnya stop melakukan capturing packet dengan menekan ikon berbentuk kotak merah dipojok kiri atas.

   <img width="317" alt="Image" src="https://github.com/user-attachments/assets/b9b3329e-33ed-4adc-a50c-0baabc900c8a" />

7. Selanjutnya lihat properties dari packet capture yang dilakukan. Dengan menekan Statistics > Caputre File Properties.

   ![Image](https://github.com/user-attachments/assets/55898ffc-1f88-47c4-b1e7-2d79976e7736)

8. selanjutnya akan muncul seperti pada gambar, Perhatikan bagian Statistics pada halaman Capture File Properties. Pada halaman ini 
   kita dapat melakukan perhitungan Throughput, Packet Loss, Delay, dan Jitter.

   ![Image](https://github.com/user-attachments/assets/87e7bcd8-bb84-4f8f-96e5-3553341cd61e)

9. Hitunglah berapa Throughput, Packet Loss, Delay, dan Jitter yang didapatkan dari Statistics Wireshark yang kalian jalankan di Komputer/Laptop masing-masing.

    **Throughtput byte**
   
    jumlah bytes / Time span = hasil bytes
   
    9307489 / 270.135 = 34.454

    **Throughtput bit**

    throughtput (byte) x 8
   
    =34.454 x 8
   
    =275.639 bit/s

   **packet loss**
   
   [((paket dikirim - paket diterima) : paket diterima) x 100
   
   = (10536 - 10536) : 10536) x 100
   
   = 0 x 100
   
   = 0

   **Delay**
   
   <img width="192" alt="Image" src="https://github.com/user-attachments/assets/52f4c2dd-6a4e-4a88-928c-d78138d6f4dc" />

   <img width="347" alt="Image" src="https://github.com/user-attachments/assets/60f0bc29-306c-4cd4-bdf3-9963d1208132" />

   Delay = Time 2 – Time 1
   
   Jadi didapatkan nilai dari data delay dan rata – rata delay sebagai berikut :

   <img width="284" alt="Image" src="https://github.com/user-attachments/assets/26aa1693-9428-43af-be23-6f78a46d2715" />

   Total Delay = Menambahkan seluruh jumlah data 95 yaitu 11,742046
   
   Rata – rata Delay = Total Delay : Jumlah Paket

   = 11,742046 : 95

   =0,123600484

   **jitter**

   Berikut adalah data yang didapatkan dari nilai delay sehingga mendapatkan Jitter

   

   

   

   



    
   



    






   
