```sh
Task :
1. Cari perbedaan antara distro Ubuntu dan CentOS!
2. Apa perbedaan dari CLI & GUI?
3. Di VM masing-masing :
- Install nginx, lalu akses melalui browser/ `curl <ip kalian>`
- Ganti IP address kalian (bebas) lalu akses kembali nginx (`/etc/netplan`)
4. Terangkan fungsi systemctl dan contoh commandnya (gunakan nginx)
```
# 1. **Cari perbedaan antara distro Ubuntu dan CentOS!**
- CentOS merupakan sistem operasi berbasis Red Hat Enterprise Linux (RHEL), sedangkan Ubuntu merupakan sistem operasi berbasis Debian.
- Ubuntu memiliki fitur yang lebih banyak dibandingkan dengan CentOS, tetapi hal ini membuat Ubuntu memakan lebih banyak resource dan lebih berat untuk dijalankan.
- Ubuntu lebih mudah digunakan oleh pemula, sedangkan CentOS jauh lebih sulit untuk dipelajari dan digunakan.

# 2. **Apa perbedaan dari CLI & GUI?**
**CLI**

- Antar muka stabil dan konsisten.
- Hanya menggunakan teks.
- Lebih kompleks dan membutuhkan skill coding.
- Tidak membutuhkan ruang penyimpanan yang besar.

**GUI**

- Sering terjadi pembaruan (upgrade).
- Menggunakan grafis dan visual.
- Lebih mudah sebab tidak perlu coding.
- Membutuhkan ruang penyimpanan yang besar.

# 3. **Install nginx, lalu akses melalui browser/ `curl <ip kalian>`dan Ganti IP address kalian (bebas) lalu akses kembali nginx (`/etc/netplan`)**

Lakukan cek update dan install respository sistem terlebih dahulu
```sh
sudo apt update; sudo apt upgrade
```
Input password yang dimiliki

<p align="center">
    ![Update](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-1-Update.png)
</p>

Untuk menginstall NGINX dapat menggunakan perintah 
```sh
sudo apt install nginx
```
Selanjutnya muncul notifikasi **Do you want to continue? [Y/n]** dan ketik saja **Y**. Jika sudah maka instalasi akan berjalan.
<p align="center">
<img src="../assets/image/3. OS & Linux/2.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

Jika sudah selesai melakukan instalasi **NGINX**. Lakukan pengecekan version NGINX yang sudah di install dengan perintah 
```sh
nginx -v
```
<p align="center">
<img src="../assets/image/3. OS & Linux/3.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>


## **PERINTAH-PERINTAH PADA NGINX**

**1. NGINX STATUS**

```sh
sudo systemctl status nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/4.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

Digunakan untuk melihat status dari NGINX.
**2. ENABLE NGINX**

```sh
sudo systemctl enable nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/5.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>
**3. DISABLE NGINX**

```sh
sudo systemctl disable nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/6.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

**4. START NGINX**

```sh
sudo systemctl start nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/7.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

**5. RESTART NGINX**

```sh
sudo systemctl restart nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/11.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

**6. RELOAD NGINX**

```sh
sudo systemctl reload nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/8.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

**7. STOP NGINX**

```sh
sudo systemctl stop nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/9.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

**8. CHECK NGINX**

```sh
sudo systemctl enable nginx
```
```sh
sudo systemctl start nginx
```
```sh
sudo systemctl status nginx
```
<p align="center">
<img src="../assets/image/3. OS & Linux/10.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

Jika sudah Kalian dapat mengakses IP dari server kalian, maka akan terlihat seperti berikut:

<p align="center">
<img src="../assets/image/3. OS & Linux/12.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

# 4. **Terangkan fungsi systemctl dan contoh commandnya (gunakan nginx)**

**Systemctl** adalah alat baris perintah yang memungkinkan pengelolaan dan pemantauan sistem systemd dan manajer layanan.
Lihat status layanan NGINX saat ini menggunakan perintah di bawah ini: 
$ sudo systemctl status nginx
Hentikan layanan NGINX dengan perintah berikut: 
$ sudo systemctl stop nginx
Anda kemudian dapat memulai pencadangan layanan NGINX menggunakan perintah berikut: 
$ sudo systemctl start nginx
