
![Screenshotan](https://drive.google.com/drive/folders/1GKYBSXshgE8QM4DcnLtOpkRCSnHTRSYe?usp=drive_link)

Untuk mengambil foto dan ada filternya itu harus ubah TakePictureScreen agar mengarah ke PhotoFilterCarousel di bagian floatingActionButton. 
Di bagian PhotoFilterCarousel tambahkan imagePath di PhotoFilterCarousel agar untuk menerima gambar dari TakePictureScreen.


JAWABAN SOAL 3 DAN 4
void async adalah 2 konsep yang sering digunakan dalam fungsi asinkron, dan void ini berarti fungsinya cuman jalanin perintah tanpa menghasilkan nilai yang bisa digunaiin lagi di tempat lainnya, dan di bagian async nya sendiri itu fungsinya akan menjalankan operasi asinkron yang butuh waktu untuk selesai kayak contohnya membaca file, melakukan request jaringan atau menunggu timer. kita bisa menggunakan await di dalam dalam fungsi tersebut untuk menunggu hasil dari asinkron tadi.

============================================================================================

@immutable adalah yang menandakan ada suatu kelas atau tipe data yang bersifat tidak bisa di ubah maksudnya ini gunakan untuk memastikan bahwa semua properti dalam kelas tersebut bersifat final.
sedangkan, @override adalah suatau metode dalam kelas yang menggantikan metode yang udah ada di kelas induk (superclass) atau  interface, maksudnyaini di gunakan untuk memastikan bahwa metode tersebut bener-bener gantiin metode yang udah ada di kelas induk, jika metode @override ini tidak di temukan di kelas induk, compiler akan menghasilkan peringatan atau error. 
