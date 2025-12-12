# **WiFi Handshake Hunter**

WiFi Handshake Hunter adalah aplikasi sederhana berbasis GUI yang digunakan untuk **menganalisis file handshake Wi-Fi** (seperti *.cap, *.pcap, *.pcapng*) yang umumnya diekstrak melalui tools seperti **Wireshark**, **Aircrack-ng**, dan aplikasi jaringan lain.
Aplikasi ini dapat membaca handshake yang telah direkam dan melakukan **pengujian keamanan** menggunakan wordlist sampel untuk memastikan kekuatan kata sandi jaringan Wi-Fi Anda sendiri.

> ⚠️ **Peringatan Penting:**
> Alat ini dibuat **hanya untuk keperluan edukasi, penelitian, dan pengujian keamanan pada jaringan milik sendiri**.
> Penggunaan pada jaringan tanpa izin merupakan tindakan ilegal.

---

## **Fitur Utama**

### ✅ **Mendeteksi Handshake**

* Memindai dan menampilkan daftar BSSID/ESSID dari file handshake.
* Mengambil nilai penting seperti ANonce, SNonce, MIC, dan paket EAPOL.

### ✅ **Menguji Kekuatan Password (Wordlist Attack)**

* Menggunakan wordlist **sampel** (tidak lengkap, hanya contoh) untuk melakukan pencocokan.
* Menampilkan progres, jumlah percobaan, dan status hasil.

### ✅ **Mendukung Banyak Format File**

Aplikasi ini mendukung format file:

* `*.cap`
* `*.pcap`
* `*.pcapng`

Format tersebut biasanya berasal dari:

* **Wireshark**
* **Aircrack-ng**
* **tcpdump**
* Tools jaringan lain yang menghasilkan file capture.

### ✅ **Antarmuka GUI yang Mudah Digunakan**

* Tombol *Scan Capture*
* Tombol *WPA Crack*
* Tampilan log proses secara real-time

---

## **Tangkapan Layar**

<div align="center">
  <img src="./assets/WiFi Handshake Hunter.jpg" alt="WiFi Handshake Hunter">
</div>

---

## **Cara Menggunakan (High-Level / Tidak Mendetail)**

> ⚠️ Catatan: Agar tidak melanggar hukum, instruksi tidak akan menjelaskan langkah teknis untuk memperoleh handshake atau cara eksploitasi jaringan.

1. Siapkan file handshake Anda (misalnya dari Wireshark atau Aircrack-ng).
2. Jalankan aplikasi WiFi Handshake Hunter.
3. Klik **Scan Capture** untuk memuat file handshake.
4. Pilih SSID yang ingin diuji.
5. Tekan **WPA Crack** untuk memulai pengujian menggunakan *sample wordlist*.

Aplikasi akan menampilkan progres percobaan serta status hasil.

---

## **Batasan**

* Aplikasi ini tidak menyertakan wordlist lengkap — hanya contoh.
* Tidak dapat melakukan penangkapan handshake langsung (capture harus dibuat melalui tool lain).
* Hanya untuk riset keamanan jaringan Anda sendiri.

---

## **Lisensi**

**MIT License**.

---

## **Disclaimer Resmi**

Aplikasi ini dibuat untuk:

* Penelitian keamanan siber
* Pengujian penetrasi legal
* Pembelajaran analisis jaringan

Penggunaan untuk mengakses jaringan tanpa izin merupakan pelanggaran hukum.

---
