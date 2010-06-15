// $Id: README.txt,v 0.1.0.0 2010/06/06 21:36:31 dnc Exp $

Referensi Jenis Kelamin
------------------------

Sebelum melakukan instalasi pastikan seting database telah diubah menyesuaikan
fitur multi database. Anda harus mempunyai array untuk database default dengan
nama 'default', contoh :
$db_url['default'] = 'mysqli://root:12345@localhost/oscitydrupal';

Anda juga bisa menambahkan database baru dengan menambah array dari variabel
$db_url, contoh :
$db_url['employes'] = 'mysqli://root:12345@localhost/oscityemployes';

Pastikan konstanta "REFUMUM_DB_USE" dalam file jeniskelamin.module dan jeniskelamin.insall
sesuai dengan variabel database yang telah Anda set di file settings.php,
contoh : 'employes'

Setelah semuanya siap, lanjutkan tahap instalasi sebagai berikut...

Untuk instalasi, letakkan seluruh folder refumum ke dalam direktori modules.
Akses Administer -> Site building -> Modules dan aktifkan module Referensi Jenis Kelamin.

Fitur Tersedia
----------------------

Module ini mengatur variabel jenis kelamin yang lazim digunakan di hampir urusan administrasi
di wilayah hukum Indonesia. Anda akan menumakn informasi ini, sering digunakan.
Namun pada saat tertentu mungkin nilai variabel tersebut ternyata bisa berbeda,
sering dalam urusan ejaan, ataupun lafal, jadi sangat dianjurkan melakukan input
referensi sesuai kebutuhan. Bagi Anda yang tidak begitu memperhatikan masalah ini,
Anda bisa menggunakan fungsi default setting, yang akan mengisi nilai variabel jenis kelamin
sesuai dengan informasi yang sering digunakan.

Maintainers
-----------
Referensi Agama secara orisinil dikembangkan oleh:
Denic Wibowo, http://oscity.org

Current maintainers:
-

