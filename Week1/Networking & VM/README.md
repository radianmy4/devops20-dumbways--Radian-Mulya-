```sh
Task :
1. Perbedaan antara IP Private & Public, serta IP Dynamic & Static!
2. Buat penjelasan singkat tentang Virtualization!
3. Buat rancangan sebuah jaringan dengan spesifikasi sebagai berikut!
      - CIDR Block : 192.168.1.xxx/24
      - Subnet : 255.255.255.0
      - Gateway : 192.168.1.1
(Gunakan app.diagrams.net untuk membuat diagramnya, Referensi gambar sudah disertakan)
4. Buat step-by-step untuk menginstall Virutal Machine via VMware, Virtualbox atau VM pilihan kalian!
```
Answer :

# 1. **Perbedaan antara IP Privat & Public, serta IP Dynamic & Static!**
**IP Private**
- Untuk masalah security, IP private cukup terproteksi sebab tidak berhubungan langsung dengan IP eksternal / umum, sehingga sulit untuk diserang para hacker.
- Lingkup area bersifat local.
- IP Private tidak bersifat unik, setiap orang bebas menggunakannya.

**IP Public**
- Dapat dikenali dalam Internet dengan mudah, sebab langsung terhubung dengan Internet tanpa perlu membutuhkan proxy tertentu, server khusus, atau ditranslasikan lewat NAT.
- Lingkup area bersifat global, seluruh dunia.
- IP Publik bersifat unik, tidak ada yang sama di dunia.

**IP Dynamic**
 - Mempermudah admin dalam pembagian IP address.
 - Tidak perlu menyetting 1 per 1 host yang ada dalam jaringan.
 - Host tidak akan mengalami IP conflict karena jika IP address yang dibagikan admin telah dipakai, otomatis Host tersebut akan mencari IP lain dan merequest kembali IP ke device admin. 

**IP Static**
- Koneksi antar device pertukaran data stabil dan jarang mengalami delay.
- Bebas menentukan IP berapa yang mau dipakai sebagai IP address.
- Lebih mudah diingat karena IP address tetap.

# 2. **Buat penjelasan singkat tentang Virtualization!**
**Virtualization** sebuah teknologi yang memungkinkan sebuah sistem komputer atau server untuk menjalankan beberapa sistem operasi atau lingkungan aplikasi secara bersamaan dalam satu mesin fisik yang sama. 

# 3. **Buat rancangan sebuah jaringan dengan spesifikasi sebagai berikut!**
      - CIDR Block : 192.168.1.xxx/24
      - Subnet : 255.255.255.0
      - Gateway : 192.168.1.1
      
 ![Network](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1//Networking%20%26%20VM/img/1-1-RancanganJaringan.png)

# 4. **Buat step-by-step untuk menginstall Virutal Machine via VMware, Virtualbox atau VM pilihan kalian!**

1. [VM-Install Ubuntu](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/tree/Master/Week1/VM-InstallUbuntu)
