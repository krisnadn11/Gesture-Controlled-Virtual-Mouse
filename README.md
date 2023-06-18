# Krisna_Mouse Virtual &nbsp;[![](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse) 

Nama: Krisna Dwi Nurikhsani

NIM: 2008610

Kelas: PTE Elind-20

Mata Kuliah: Visi Komputer

# Inovasi Gesture Controlled Virtual Mouse: Mengoptimalkan Interaksi Manusia dengan Komputer melalui Gerakan Tangan. 
Gesture Controlled Virtual Mouse adalah sebuah solusi yang dirancang untuk mempermudah interaksi antara manusia dengan komputer melalui penggunaan gerakan tangan. Dengan menggunakan teknologi ini, komputer dapat dikendalikan secara virtual tanpa perlu kontak langsung. Semua operasi input/output dapat dikontrol melalui gerakan tangan statis dan dinamis.

Proyek ini menggunakan algoritme Machine Learning dan Computer Vision yang canggih untuk mengenali gerakan tangan. Algoritme ini bekerja dengan baik tanpa memerlukan perangkat keras tambahan. Salah satu model yang digunakan adalah Convolutional Neural Network (CNN) yang diimplementasikan oleh MediaPipe. Proyek ini saya buat untuk memnuhi tugas Mata Kuliah Visi Komputer.

# Fitur
_Klik dropdown untuk melihat fitur pada proyek yang telah saya buat_ <br>

### Pengenalan Gerakan
<details>
<summary>Gerakan Netral</summary>
  <img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Gerakan%20Netral.gif" alt="Gerakan Netral" width="771" height="400"><br>
  <figcaption>Gerakan Netral, digunakan untuk menahan atau menghentikan eksekusi gerakan saat ini.</figcaption>
</details>
 
<details>
<summary>Memindahkan Kursor</summary>
  <img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Memindahkan%20Kursor.gif" alt="Memindahkan Kursor" width="771" height="400"><br>
  <figcaption>Kursor ditetapkan ke titik tengah telunjuk dan ujung jari tengah. Gerakan ini memindahkan kursor ke lokasi yang diinginkan. Kecepatan gerakan kursor kurang lebih sebanding dengan kecepatan tangan.</figcaption>
</details>

<details>
<summary>Klik Kiri</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Klik%20Kiri.gif" alt="Klik Kiri" width="771" height="400"><br>
 <figcaption>Gerakan untuk sekali klik kiri</figcaption>
</details>

<details>
<summary>Klik Kanan</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Klik%20Kanan.gif" alt="Klik Kanan" width="771" height="400"><br>
 <figcaption>Gerakan untuk sekali klik kanan</figcaption>
</details>

<details>
<summary>Klik 2x</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Klik%202x.gif" alt="Klik 2x" width="771" height="400"><br>
 <figcaption>Gerakan untuk klik kiri 2x</figcaption>
</details>

<details>
<summary>Seret dan Lepas V1</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Seret%20dan%20Lepas%20V1.gif" alt="Seret dan Lepas V1" width="771" height="400"><br>
 <figcaption>Gerakan fungsional untuk seret dan lepas. Dapat digunakan dalam menyeret/memindahkan file dari satu folder ke folder lainnya</figcaption>
</details>

<details>
<summary>Seret dan Lepas V2</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Seret%20dan%20Lepas%20V2.gif" alt="Seret dan Lepas V2" width="771" height="400"><br>
 <figcaption>Tidak jauh beda seperti gerakan sebelumnya, namun gerakan ini lebih mudah saat dipraktikan.</figcaption>
</details>

<details>
<summary>Memilih Beberapa Item</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Memilih%20Beberapa%20File.gif" alt="Memilih Beberapa File" width="771" height="400"><br>
 <figcaption>Gerakan untuk memilih beberapa file</figcaption>
</details>

<details>
<summary>Kontrol Volume</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Kontrol%20Volume.gif" alt="Kontrol Volume" width="771" height="400"><br>
 <figcaption>Gerakan Dinamis untuk kontrol Volume. Laju kenaikan/penurunan volume sebanding dengan jarak yang dipindahkan oleh gerakan mencubit dari titik awal. </figcaption>
</details>

<details>
<summary>Kontrol Kecerahan Layar</summary>
<img src="https://github.com/krisnadn11/Gesture-Controlled-Virtual-Mouse/blob/main/Demo%20Proyek%20Visi%20Komputer/Kontrol%20Kecerahan%20Layar.gif" alt="Kontrol Kecerahan Layar" width="771" height="400"><br>
 <figcaption>Gerakan Dinamis untuk kontrol Kecerahan. Laju peningkatan/penurunan kecerahan sebanding dengan jarak yang dipindahkan oleh gerakan mencubit dari titik awal. </figcaption>
</details>

# Cara Menggunakannya
### Prasyarat

Python: (3.6 - 3.8.5)<br>
Install Anaconda: Untuk mengunduhnya, klik [ di sini ](https://www.anaconda.com/products/individual).

Unduh dan ekstrak folder yang bernama Virtual-Mouse-main, kemudian buka folder tersebut di VsCode, buka terminal dan pastikan terkonfigurasi dengan PowerShell bukan Command Prompt

### Langkah-langkah

  Langkah 1:
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Langkah 2:
  ```bash
  conda activate gest
  ```
  
  Langkah 3:  
  ```bash
  pip install -r requirements.txt
  ```
  
  Langkah 4:
  ```
  cd src
  ```
  Ubah directory ke src. Perintah mungkin akan terlihat seperti: `cd C:\Users\.....\Virtual-Mouse\src>`
  
  
  Langkah 5:
  
  Untuk menjalankan Virtual Mouse:
  ```bash 
  python Virtual_Mouse.py
  ```
