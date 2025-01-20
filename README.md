# Windows RDP Installer

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/FighterTunnel/tunnel)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-green)](https://GitHub.com/FighterTunnel/tunnel/graphs/commit-activity)
[![GitHub Forks](https://img.shields.io/github/forks/FighterTunnel/tunnel?&logo=github)](https://github.com/FighterTunnel/tunnel/fork)
[![GitHub Stars](https://img.shields.io/github/stars/FighterTunnel/tunnel?&logo=github)](https://github.com/FighterTunnel/tunnel/stargazers)

## Deskripsi
Repositori ini berisi skrip dan panduan untuk menginstal dan mengonfigurasi Remote Desktop Protocol (RDP) pada sistem operasi Windows. RDP memungkinkan pengguna untuk terhubung ke komputer Windows dari jarak jauh, memberikan akses penuh ke desktop, aplikasi, dan file.

![Screenshot](https://www.bleepstatic.com/content/hl-images/2024/05/14/Windows-Server.jpg)

## Fitur
- Instalasi mudah dan cepat untuk RDP pada Windows.
- Konfigurasi pengaturan RDP sesuai kebutuhan pengguna.
- Dukungan untuk berbagai versi Windows (Windows 10, Windows Server, dll.).

## Prerequisites
- Sistem operasi Windows yang kompatibel.
- Koneksi internet untuk mengunduh pembaruan dan driver yang diperlukan.
- Autosetup Interface IP RDP

## Install Otomatis Dengan 1 Klik
```
wget https://raw.githubusercontent.com/FighterTunnel/rdp/main/image/auto.sh && bash auto.sh
```
## Install Manual
1. **Windows 10**
```
wget -O- --no-check-certificate https://image.yha.my.id/2:/windows10.gz | gunzip | dd of=/dev/vda
```
2. **Windows Server 2012 R2**
```
wget -O- --no-check-certificate https://image.yha.my.id/2:/indows2012.gz | gunzip | dd of=/dev/vda
```
3. **Windows Server 2016**
```
wget -O- --no-check-certificate https://image.yha.my.id/2:/windows2016.gz | gunzip | dd of=/dev/vda
```
4. **Windows Server 2019**
```
wget -O- --no-check-certificate https://image.yha.my.id/2:/windows2019.gz | gunzip | dd of=/dev/vda
```
5. **Windows Server 2022**
```
wget -O- --no-check-certificate https://image.yha.my.id/2:/windows2022.gz | gunzip | dd of=/dev/vda
```

## Ikuti Petunjuk di Layar
<details>
<summary><b>🔗 Remote Desktop Protocol Detail Login</b></summary>

### Remote Desktop Protocol Detail Login

-  RDP HOST/IP PORT `5888`
-  Username `Administrator`
-  Password `@Ftvpnstores`
</details>



<h3 align="center">Sangat disarankan mengganti password!!!</h3>

## Kontribusi
Kami menyambut baik kontribusi dari komunitas! Silakan buka isu atau kirim pull request jika Anda memiliki saran atau perbaikan.

## Lisensi
Repositori ini dilisensikan di bawah [Raphielscape Public License](https://raw.githubusercontent.com/FighterTunnel/rdp/main/LICENCE) - Version 1.d, Agust 2024

Anda dapat menyesuaikan bagian-bagian tertentu sesuai dengan kebutuhan spesifik proyek Anda
