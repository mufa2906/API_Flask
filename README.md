# API_Flask
Creating simple API with Flask(Python Framework)

Source Learning(SL):
  - REST API Crash Course - Introduction + Full Python API Tutorial
  - link : https://www.youtube.com/watch?v=qbLc5a9jdXo
 
Urutan Kerja :
  - Membuat Venv dengan command : "python -m venv venv"
  - Menginstall flask dan flask_sqlalchemy
  - Menginstall python-dotenv untuk mempermudah env flask
  - Membuat file .env sehingga dapat menjalankan flask langsung menggunakan terminal dengan command "flask run"
  - Membuat file application.py yang berisi app flask, koneksi database dan API
  - membuat database(menggunakan sqlite, dimana tabel sudah di definisikan pada file application.py dan di run pada flask shell dengan command "db.create.all()"
  - Membuat routing API (GET, POST, DELETE)
  - Saat POST dan DELETE menggunakan software POSTMAN
  - Selesai
  
Kendala :
  - Ada sedikit perbedaan dengan SL  pada saat menjalankan flask pertama kali karena menggunakan Windows 11(SL menggunakan UNIX/LINUX)
    referensi : How to Create A Simple Flask Application on Windows, link: https://medium.com/@albertnwachukwu/how-to-create-a-simple-flask-application-9be43f9aadcd
  - saat membuat database, ternyata memerlukan syntaks app_context().push() jika menggunakan Python shell
    Menggunakan Flask shell sehingga command yang digunakan sama dengan SL
