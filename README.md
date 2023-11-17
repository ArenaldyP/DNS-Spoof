# ARP Sniffer and Spoofing Tool
# Deskripsi:
Proyek ini menyediakan alat sederhana untuk mendeteksi dan melakukan spoofing terhadap protokol ARP dalam jaringan. Menggunakan Python dan Scapy, alat ini dapat digunakan untuk analisis keamanan jaringan atau tujuan pendidikan.

# Kode DNS Spoofer
# Deskripsi:
Implementasi DNS spoofing menggunakan NetfilterQueue dan Scapy dalam bahasa pemrograman Python. Proyek ini memungkinkan pengguna untuk mendeteksi permintaan DNS untuk domain-domain tertentu dan menggantikan respons DNS dengan alamat IP yang telah ditentukan. Cocok untuk eksperimen keamanan siber dan pemahaman dasar tentang manipulasi paket dalam jaringan.

# Cara Menjalankan
## 1
### sudo iptables -I FORWARD -j NFQUEUE --queue-num 0 --queue-bypass
setting ip tables agar packet ter Forward

## 2
jalankan ARP_Spoof.py

## 3
Lalu jalankan DNS_Spoof.py 

## 4 
Jangan Lupa dengan apache pada kali dijalankan
### sudo service apache2 start 
agar website spoof menuju website penyerang

## 4
Jika korban mengunjungi website yang kita Spoof akan berubah dan menuju ip website penyerang

Dengan Begitu kita dapat membuat website yang serupa dengan Spoof website dan bisa mendapatkan kredensial dari korban

