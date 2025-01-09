# Tugas Akhir/Mandiri PCD - Deteksi Botol Menggunakan YoloV8

<b>Setup Projek</b>
- Membuat Virtual Environment dengan menjalankan perintah <br> ``` py -m venv .venv ```
- Mengaktifkan virtual environment dengan menjalankan perintah <br> ``` .venv\Scripts\activate ``` direkomendasikan menggunakan CMD/Command Line
-Install library <em>ultralytics</em> agar dapat mengimplementasikan YOLO V8, untuk menginstall jalankan perintah ``` pip install ultralytics ```
- install cv2 untuk menyimpan gambar pada folder output <br> ``` pip install opencv-python-headless ```
- Buat folder bernama <em>input_images</em> pada root direktori, folder tersebut digunakan untuk menampung image yang akan di deteksi.

<b>Cara Running</b>
- jalankan perintah berikut untuk me running program <br> ``` py main.py ```