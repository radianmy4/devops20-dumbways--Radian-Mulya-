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

![hostname](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Challenge/img/1-1-Hostname.png)
# 2. **Buat network adapter baru dengan nama ens20 dan gunakan IP yang sama**

Command untuk merubah nama network adapter
```sh
sudo nano /etc/netplan/00-install-config.yaml
```
![adapter](https://github.com/radianmy4/devops20-dumbways--Radian-Mulya-/blob/Master/Week1/Challenge/img/1-2-AdaperBaru.png)
