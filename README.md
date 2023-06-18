# Gesture-Controlled-Virtual-Mouse
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
<summary>Neutral Gesture</summary>
 <figure>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/palm.gif" alt="Palm" width="711" height="400"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>
 

<details>
<summary>Move Cursor</summary>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/e20edfb1f368ffa600d96bd91031942ec97cb2ab/demo_media/move%20mouse.gif" alt="Move Cursor" width="711" height="400"><br>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/left%20click.gif" alt="Left Click" width="711" height="400"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/right%20click.gif" alt="Right Click" width="711" height="400"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/double%20click.gif" alt="Double Click" width="711" height="400"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Scrolling</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Scrolling.gif" alt="Scrolling" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for horizontal and vertical scroll. The speed of scroll is proportional to the distance moved by pinch gesture from start point. Vertical and Horizontal scrolls are controlled by vertical and horizontal pinch movements respectively.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/drag%20and%20drop.gif" alt="Drag and Drop" width="711" height="400"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

<details>
<summary>Multiple Item Selection</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/multiple%20item%20selection.gif" alt="Multiple Item Selection" width="711" height="400"><br>
 <figcaption>Gesture to select multiple items</figcaption>
</details>

<details>
<summary>Volume Control</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Volume%20control.gif" alt="Volume Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Volume control. The rate of increase/decrease of volume is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

<details>
<summary>Brightness Control</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Brigntness%20Control.gif" alt="Brightness Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Brightness control. The rate of increase/decrease of brightness is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

# Cara Menggunakannya
### Prasyarat

Python: (3.6 - 3.8.5)<br>
Distribusi Anaconda: Untuk mengunduh, klik [ di sini ](https://www.anaconda.com/products/individual).

Unduh dan ekstrak folder yang bernama Virtual-Mouse.
Dan kemudian Buka Folder Virtual-Mouse di VsCode.

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
  Change Directory ke src. Perintah mungkin terlihat seperti: `cd C:\Users\.....\Virtual-Mouse\src>`
  
  
  Langkah 5:
  
  Untuk menjalankan Virtual Mouse:
  ```bash 
  python Virtual_Mouse.py
  ```
