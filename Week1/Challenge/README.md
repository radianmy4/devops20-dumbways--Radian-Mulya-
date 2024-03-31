```sh
Challenge :
1. Rubah nama hostname menjadi "dumbways"
2. Buat network adapter baru dengan nama ens20 dan gunakan IP yang sama
```
# 1. **Rubah nama hostname menjadi "dumbways"**
Command untuk merubah nama hostname
```sh
hostnamectl set-hostname "dumbways"
```
Command untuk check nama hostname
```sh
hostnamectl
```
# 2. **Buat network adapter baru dengan nama ens20 dan gunakan IP yang sama**

Command untuk merubah nama network adapter
```sh
sudo nano /etc/netplan/00-install-config.yaml
```
<p align="center">
<img src="../Week 1/image challange/Change Name Adapter.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>

Lakukan restart connection

```sh
sudo netplay try
```
Menyalakan network kembali
```sh
sudo netplay apply
```

Check apakah nama adapter sudah berubah
```sh
ip a
```
<p align="center">
<img src="../Week 1/image challange/check adapter.JPG" alt="Alt text" title="Client - Server" style="display: inline-block; margin: 0 auto;  max-width: 300px ">
</p>
Lakukan check connection

```sh
ping 8.8.8.8
```
