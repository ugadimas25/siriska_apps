README: 
=================================================

Daftar Isi
-----------------

* [Pengantar](#pengantar)
* [Data](#data)
* [Desain Sistem](#desain-sistem)
* [Library](#library)
* [Live Demo](#live-demo)
* [Issue](#issue)
* [Acknowledgments](#acknowledgments)



Pengantar
------------
Project ini merupakan hasil dari pengembangan tesis saya di Prodi Master Teknik Geomatika, Departemen Teknik Geodesi, Universitas Gadjah Mada. 


Data
------------

Data irigasi (bangunan irigasi, saluran irigasi dan petak irigasi) Kecamatan Matesih dan Kecamatan KarangpandanKabupaten Karanganyar yang diperoleh dari DPUPKP Kabupaten Karanganyar. Data irigasi tersebut merupakan data spasial berformat vektor berupa data shapefile dengan luas wilayah kurang dari 10.000 ha.

Data iklim (suhu udara dengan satuan ℃, kelembaban udara rata-rata dengan satuan %, kecepatan angin rata-rata dengan satuan %, dan curah hujan dengan satuan mm) Kecamatan Matesih dan Kecamatan Karangpandan Kabupaten Karanganyar. Data tersebut merupakan data nonspasial diperoleh dari Stasiun Staklim BMKG Kelas I Semarang.

Data Porositas Tanah kecamatan Matesih dan Kecamatan KarangpandanKabupaten Karanganyar. Data tersebut merupakan data nonspasial yang diperoleh dari Dinas Pertanian dan Pangan Kabupaten Karanganyar.


Desain Sistem
------------
Berdasarkan analisis kebutuhan pengguna dan kebutuhan sistem didapatkan infrastruktur sistem backend yang dibuat yaitu terdiri atas tiga komponen utama yaitu web server, server side scripting dan database. Untuk infrastruktur frontend yang dibuat terdiri atas tiga komponen utama yaitu HTML5, CSS dan JavaScript.
Salah satu kelebihan dari webmap **SIRISKA** ini yaitu selain memiliki fungsi CRUD (Create Read Update Delete) juga dapat melakukan 

Skema Basidata
------------
Pembangunan basisdata yang dilakukan terdiri atas dua tahapan utama yaitu konseptual, fisikal
* Basisdata Konseptual
![](https://github.com/ugadimas25/siriska_apps/blob/main/assets/images/Tesis_Dimas-Basis%20Data%20konseptual.png)

* Basisdata Fisikal



Library
-----
Leaflet.js

Interface
---------------


Tampilan Setelah Login
![](https://github.com/ugadimas25/siriska_apps/blob/main/assets/images/interface_setelah_login.jpg)

Issue
-----
Terkait Cross-Origin resource data
Jika data tidak terload ada kemungkinan issue terkait CROS, Origin Policy disallows reading the remote resource, atau perubahan policy pengaturan izin reading data, hanya boleh dalam satu domain yang sama dengan resource service. 

Acknowledgments
---------------

[MapBox](https://www.mapbox.com/)

[HealthMap](https://www.healthmap.org/en/)

[Open Data Working Group COVID-19 Global](https://github.com/beoutbreakprepared/nCoV2019/)

[The World Air Quality Project EPA Worldwide](https://aqicn.org/contact)


