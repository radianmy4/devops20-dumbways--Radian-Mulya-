# Dumbways Bootcamp DevOps
## Week 1
### VM-Install Ubuntu

1. Untuk membuat Virtual Machine baru, klik "Create a New Virtual Machine".
    
    ![VM](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-1-BuatVMbaru.png)

2. Lalu pilih versi Operating System yang ingin diinstall berformat iso.

    ![File](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-2-LokasiFileISO.png)

3. Isi data Username dan beri nama untuk Virtual Machine baru.
    
    ![Username](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-3-UsernameVM.png)
    ![Nama](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-4-NamaVM.png)

4. Buat Virtual Harddisk, dengan mengisi kapasitas yang diinginkan dan memilih split virtual disk.

    ![VDI](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-5-MembuatVirtualHarddisk.png)

5. Lalu pilih customize Hardware.
    
    ![Hardware](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-6-CustomizeHardware.png)

6. Alokasikan ukuran RAM yang akan digunakan server. Disini digunakan 1 GB RAM.
    
    ![RAM](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-7-Ram.png)

7. Alokasikan ukuran Core Processors yang akan digunakan server. Disini digunakan 1 Core.
    
    ![CPU](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-8-Processors.png)

8. Untuk Network Adapter Pilih Bridge lalu Configure Adapter Pilih Network Adapter yang ingin digunakan. Disini digunakan Wifi 
    
    ![Network](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-9-NetworkAdapter.png)

9. Pilih bahasa yang digunakan.
    
    ![Bahasa](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-10-Bahasa.png)

10. Kemudian disini mengconfigurasi network connections dari DHCP ke manual.
    
    ![DHCP](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-11-NetworkConection.png)
    ![DHCP](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-12-IPv4Manual.png)

11. Untuk mengetahui IP kita bisa menggunakan CMD dan ketik perintah “iponfig”.
    
    ![IPa](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-13-ManualIPdanCMDIPconfig.png)

12. Konfigurasi storage. Karena akan dilakukan partisi secara manual, dipilih Custom lalu memilih HDD yang tersedia (VDI).

    ![Storage](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-14-AlokasiStorage.png)

13. Buat partisi pada server. Dialokasikan 1.8 GB untuk swap, dan 8 GB untuk root.
    
    ![partisi](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-15-Partisi.png)

14. Setup Profile.

    ![profile](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-16-SetupProfile.png)

15. Pilihan untuk menginstall aplikasi. Karena akan dilakukan secara manual satu per satu, step ini dilewati dengan tanpa memilih satupun.

    ![aplikasi](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-17-AppServer.png)

16. Tunggu proses instalasi Server hingga selesai.

    ![Installing](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-18-Installing.png)

17. Setelah selesai, lakukan Login ke Server.

    ![Login](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/VM-InstallUbuntu/img/1-19-Login.png)
