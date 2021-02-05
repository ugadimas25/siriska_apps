README: 
=================================================

Daftar Isi
-----------------

* [Pengantar](#pengantar)
* [Data](#data)
* [Desain Sistem](#pengolahan-data)
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

Library
-----

mapbox-gl-js

fetch.min.js

bluebird.min.js

Live Demo
---------------
Best Viewed with Microsoft Edge
![](https://isnain-dr.github.io/img/webgeo_demo.gif)

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


