<p align="center" >
  <b>POINT UTAMA</b>
</p>

---

> #### SEJARAH MVC
> - Sejarah Model-View-Controller (MVC) pertama kali diperkenalkan pada tahun 1970 oleh Trip Ransquawk di Xerox Palo Alto Research.
> - Konsep MVC terbagi menjadi tiga bagian: model, view, dan controller.
> - MVC sederhana namun bisa menjadi kompleks dalam pengembangan aplikasi yang rumit, kadang-kadang membutuhkan pola desain dan paten perangkat lunak tambahan.
---
> #### PUBLIC DIRECTORY
> - Praktek terbaik adalah tidak mengekspos seluruh kode PHP ke web, tetapi hanya mengekspos folder publik yang berisi file yang dibutuhkan.
>
> Berikut struktur project :
>
> <img width="176" alt="Cuplikan layar 2024-03-27 083008" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/4f111103-acb7-4384-99e8-ac51e5d27ac8">
---
> #### PATH_INFO
> - Pathinfo adalah informasi bagian dari URL yang mengandung informasi tambahan, seperti nama file atau parameter query.
> - Pathinfo dapat dimanfaatkan untuk mengarahkan permintaan HTTP ke file yang sesuai tanpa perlu menambahkan nama file dalam URL.
>
> Berikut kode PATH_INFO :
>
> <img width="293" alt="Cuplikan layar 2024-03-27 083024" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/088c6933-8610-4205-bbad-ef75c11d88b3">
>
> #### UNTUK APA PATH_INFO?
> - PATH_INFO ini banyak digunakan sabagai URL Routing
> - Routing adalah teknik menentukan rute dari URL ke file PHP yang akan dieksekusi, memungkinkan penanganan permintaan HTTP sesuai dengan URL yang diminta.
>
> Berikut kode routing sederhana :
>
> <img width="388" alt="Cuplikan layar 2024-03-27 083044" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/03058038-dede-41cd-8323-fc9630aa9831">
---
> #### ROUTER
> - Routing sederhana menggunakan pathinfo memungkinkan kita untuk menentukan file mana yang akan diakses berdasarkan bagian dari URL yang dikirimkan.
> - Routing dalam aplikasi MVC melibatkan pemetaan antara URL, metode HTTP, dan fungsi kontrol yang sesuai.
>
> Berikut kode class router :
>
> <img width="453" alt="Cuplikan layar 2024-03-27 083209" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/63530fc6-4178-407c-9a30-7c1963f51314">
>
> Berikut kode menambah url mapping :
>
> <img width="402" alt="Cuplikan layar 2024-03-27 083345" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/3b66f6e0-c943-48c1-80d2-22e85f2027a6">
>
> Berikut kode memilih controller :
>
> <img width="523" alt="Cuplikan layar 2024-03-27 083453" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/513528a3-e8e7-4da7-8f59-a7dda3ea9db2">
>
> Berikut kode menggunakan router :
>
> <img width="454" alt="Cuplikan layar 2024-03-27 083934" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/3a1ad53b-37fe-486e-8549-811d3c72cd1f">
---
> #### CONTROLLER
> - Controller dalam MVC bertanggung jawab untuk mengeksekusi fungsi yang sesuai berdasarkan pada permintaan yang diterima dan pemetaan yang telah ditentukan.
> - Setelah pemetaan URL dilakukan, selanjutnya adalah membuat controller yang akan menerima permintaan dan melakukan pemrosesan logika aplikasi.
>
> Berikut kode home controller :
>
> <img width="312" alt="Cuplikan layar 2024-03-27 084109" src="https://github.com/weyndraig14/belajar-php-mvc/assets/162102805/cf79d08d-03cc-48be-af07-b174f88569dd">
---


<p align="center" >
  <b>KESIMPULAN</b>
</p>

> - Dapat membantu dalam membangun sistem pengembangan website yang terdiri dari tiga bagian yaitu model, view, dan controller.








