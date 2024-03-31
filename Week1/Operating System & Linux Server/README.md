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
sudo apt update
```
Input password yang dimiliki    

 ![update](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-1-Update.png)

```sh
sudo apt upgrade
```

 ![upgrade](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-2-Upgrade.png)

Untuk menginstall NGINX dapat menggunakan perintah 
```sh
sudo apt install nginx
```
Selanjutnya muncul notifikasi **Do you want to continue? [Y/n]** dan ketik saja **Y**. Jika sudah maka instalasi akan berjalan.

![Install](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-3-InstallNginx.png
)

**akses melalui browser/ `curl <ip kalian>`**

![curl](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-4-NginxBrowser.png
)

**Ganti IP address kalian (bebas) lalu akses kembali nginx (`/etc/netplan`)**

![curl](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-5-GantiIP.png
)

**akses melalui browser/ `curl <ip yang sudah diganti>`**

![curl](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-6-SetelehGanti.png
)


# 4. **Terangkan fungsi systemctl dan contoh commandnya (gunakan nginx)**

**Systemctl** adalah alat baris perintah yang memungkinkan pengelolaan dan pemantauan sistem systemd dan manajer layanan.
Lihat status layanan NGINX saat ini menggunakan perintah di bawah ini: 
```sh
sudo systemctl status nginx
```

![status](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-7-StatusNginx.png)

Anda kemudian dapat memulai pencadangan layanan NGINX menggunakan perintah berikut: 
```sh
sudo systemctl start nginx
```

![status](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-8-StartNginx.png)


Hentikan layanan NGINX dengan perintah berikut: 
```sh
sudo systemctl stop nginx
```

![status](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Operating%20System%20%26%20Linux%20Server/img/1-9-StopNginx.png)
