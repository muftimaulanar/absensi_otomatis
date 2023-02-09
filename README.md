# Smart Absensi dengan Face Detection
Program smart absensi ini menggunakan bahasa pemrograman python dan algoritma haarcascade. Pengenalan wajah menggunakan haarcascade_frontalface_default, sedangkan untuk pengenalan mata menggunakan haarcascade_eye. <br />
a. Untuk wajah (https://github.com/kipr/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml) <br /> 
b. Untuk mata (https://github.com/kipr/opencv/blob/master/data/haarcascades/haarcascade_eye.xml) <br />
Dalam project ini, dibuat sebuah sistem kehadiran mahasiswa dengan menggunakan teknologi pengenalan wajah menggunakan bahasa pemrograman python dan algoritma haarcascade. Pada sistem ini dibuat GUI (Graphical User Interface) untuk mempermudah user/mahasiswa melakukan absensi kehadiran. Terdapat 3 menu utama pada sistem ini. Antara lain adalah Inisialisasi wajah, Training, dan Absensi otomatis. Sistem ini dibuat dengan spyder 3 (python 3.9) dan juga anaconda 3 2022.

# Python Library
Pada project ini digunakan beberapa library untuk menunjang sistem. Diantaranya adalah:<br />
  a. openCV (mengolah image atau video sesuai dengan tujuan masing-masing yang melibatkan kamera untuk menangkap gambar lalu diolah di komputer) <br />
  b. tkinter (merupakan sebuah GUI yang digunakan oleh python secara build in yang artinya tidak perlu menginstall tambahan yang lain) <br />
  c. os (modul python yang memungkinkan untuk melakukan operasi yang terkait dengan sistem operasi) <br />
  d. numpy (library python yang fokus pada scientific computing) <br />
  e. datetime (digunakan untuk memanggil dan menampilkan waktu pada proses ataupun hasil disuatu sistem)

## Prinsip Kerja Sistem
1. Running file **Absen dengan Face Detection.py**
2. Masukkan data yang diminta seperti Nama, NIM, dan Kelas (khusus NIM harus angka)
3. **Inisialisasi wajah** untuk mengambil sampel wajah
4. **Training** untuk melatih program mengenali wajah
5. **Absensi otomatis** untuk melakukan absen menggunakan wajah yang telah dilatih
6. Tekan **q** di keyboard untuk keluar dari kamera
7. Absensi telah dilakukan dan data sudah masuk kedalam file excel "Kehadiran.csv"

## Langkah Instalasi Sistem
1. Buka anaconda 3 dan spyder/visual studio code (pastikan environment dan path ke power shell python sudah benar)
2. Buka file python **Absen dengan Face Detection.py**
3. Running dan compile file tersebut
4. Masuk ke GUI sistem, input data yang diminta seperti nama, NIM, dan kelas (khusus NIM harus angka)
