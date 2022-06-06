# Lab11Web
# Praktikum 11 PHP Framework 
Langkah-langkah Praktikum
1. Siapkan Vscode
2. Buat folder baru bernama lab11_php_ci di webserver htdocs
3. jalankan xampp, sebelum melakukan start klik apache>config, kemudian pilih PHP (php.ini)
![image 1](screenshot/ss2.PNG)
![image 2](screenshot/sss1.PNG)
Kemudian, hilangkan (;)pada ekstensi
- php-json
- php-mysqlnd
- php-xml
- php-intl
- libcurl
![image 3](screenshot/ss1.PNG)
setelah (;) dihilangkan, langkah selanjutnya adalah klik start pada xampp apache

# Installasi Codeigniter 4
1. unduh Codeigniter dari website https://codeigniter.com/download
![image 4](screenshot/ss3.PNG)
2. kemudian download, dan extrak file ke direktori htdocs/lab11_php-ci
![image 5](screenshot/ss4.PNG)
3. setelah file di extrak ganti nama file tersebut menjadi ci4
![image 6](screenshot/ss5.PNG)
4. kemudian akses localhost/lab11_php_ci/ci4
![image 7](screenshot/ss6.PNG)
5. Akses ocalhost/lab11_php_ci/ci4/public/
![image 8](screenshot/ss7.PNG)
6. jalankan CLI codeigniter 4 dengan mengakses CLI xampp. Dan ketikan perintah # cd htdocs\lab11_php_ci\ci4 untuk mengarahkan direktori kerja yang di buat
![image 9](screenshot/ss8.PNG)
7. ketikan perintah # php spark untuk memanggil CLI Codeigniter
![image 10](screenshot/ss9.PNG)

# Mengaktifkan mode Debugging
1. untuk memudahkan developer untuk mengetahui pesan error apabila terjadi kesalahan.
Dengan mengubah nilai konfigurasi pada environment variabel CI_ENVIRONMENT menjadi development
![image 11](screenshot/ss10.PNG)
Ubah file env menjadi.env dan buka file ubah nilai variabel nya
![image 12](screenshot/ss11.PNG)
2. Langkah selanjutnya adalah mengubah kode file app/controller/Home.php
hilangkan (;) yang ada di belakang message
![image 13](screenshot/ss12.PNG)
kemudian refresh kembali browser
![image 14](screenshot/ss13.PNG)
3. buka file app/config/Routes.php
![image 15](screenshot/ss14.PNG)
tambahkan 3 source code dibawah
4. Kemudian buka CLI xampp kembali, dan ketikan perintah # php spark routes
![image 16](screenshot/ss15.PNG)

# Membuat Controller
Buat file baru dengan nama page.php pada direktori Controller, isi dengan script page.php
hasil setelah akses lovalhost/lab11_php_ci/c4/public/about
![image 17](screenshot/ss16.PNG)
![image 18](screenshot/ss17.PNG)

# Membuat View
Buat file baru di directory app/view/about.php
isi dengan kode yang ada di about.php
![image 19](screenshot/ss18.PNG)

# Membuat layout Web dengan CSS
buat file css pada direktory public dengan nama style.css , kemudian copy file dari praktikum 4.
![image 20](screenshot/ss19.PNG)
