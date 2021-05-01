#### Apa itu RestAPI?

sebelumnya, API adalah singkatan dari Application Programming Interface yaitu sebuah software
yang memungkinkan para developer untuk mengintegrasikan dan mengizinkan dua aplikasi yang
berbeda secara bersamaan untuk saling terhubung satu sama lain.
Tujuan penggunaan dari API adalah untuk saling berbagi data antar aplikasi yang berbeda
tersebut, dan juga untuk mempercepat proses pengembangan aplikasi dengan cara menyediakan
sebuah function yang terpisah sehingga para developer tidak perlu lagi membuat fitur yang
serupa.

REST API merupakan salah satu dari desain arsitektur yang terdapat di dalam API itu
sendiri. Dan cara kerja dari RESTful API yaitu REST client akan Melakukan akses pada
data/resource pada REST server dimana masing-masing resource. Atau data/resource tersebut
akan dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
Jadi, Nantinya data yang diberikan oleh REST server itu bisa berupa format text, JSON atau
XML. Dan saat ini format yang paling populer dan paling banyak digunakan adalah format
JSON.

Adapun metode HTTP yang secara umum dipakai dalam REST api adalah:
• GET, berfungsi untuk membaca data/resource dari REST server
• POST, berfungsi untuk membuat sebuah data/resource baru di REST server
• PUT, berfungsi untuk memperbaharui data/resource di REST server
• DELETE, berfungsi untuk menghapus data/resource dari REST serve
• OPTIONS, berfungsi untuk mendapatkan operasi yang disupport pada resource dari
REST server.

Retrofit adalah sebuah library android yang membantu pengembang untuk melakukan
request ke sebuah endpoint REST API. Library ini dikembangkan oleh Square Inc
(https://github.com/square) sebuah perusahaan yang berbasis di Amerika Serikat. Library ini
menyederhanakan kode program yang digunakan untuk mengakses REST API. Tidak hanya untuk
mengakses REST API dengan proses sederhana (GET, POST, PUT, DELETE) retrofit juga
mendukung berbagai macam format authentikasi via http, menambahkan header pada request,
menambahkan parameter serta mengirim data berupa image ke server.
Untuk mengakses REST api dengan kode program bawaan android seorang programmer
harus membuat banyak worker dan thread menggunakan Async Task. Hal ini bukan sebuah proses
yang sederhana, apalagi jika request terhadap API tersebut menuntut adanya security, parameter
khusus yang harus ditambahkan atau bahkan mengirim data selain text contoh berupa gambar ke
server. Jika menggunakan Async Task dapat dipastikan programmer akan kesulitan dalam
membuat program. Akan lebih baik jika semua proses yang berhubungan dengan networking
tersebut ditangani oleh Retrofit. kita akan mencoba mengambil data dari
http://www.omdbapi.com/?s=batman&apikey=2268147d.

### Example of RestAPI project:

Day Mode

![Day Mode](https://github.com/NextDvn/Rest_Api/blob/master/Day%20Mode.png)

Night Mode

![Night Mode](https://github.com/NextDvn/Rest_Api/blob/master/Dark%20Mode.png)
