<h1>B. Transmisi Data Menggunakan HTTP</h1>
<b><p>Alat dan Bahan</p></b>
<p>1. ESP 32</p>
<p>2. XAMPP</p>
<p>3. Node-Red</p>
<br></br>
<h1>Metode GET</h1>
<p>Source Code</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Penjelasan%20Kode%20metode%20GET.jpeg?raw=true)


<p>Flow Chart</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/1.%20Flow%20Chart%20program%20ESP32%20metode%20GET.png?raw=true)

<p>Flow Chart Program</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Flow%20Program%20get.jpeg?raw=true)


<p>Tabel Database MySQL </p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/5.%20Tabel%20database%20MySQL%20get.jpeg?raw=true)


<p>Output Serial monitor</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/2.%20Output%20serial%20monitor%20metode%20get.jpeg?raw=true)

<p>Dashboard Node-Red </p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/4.%20Dashboard%20Node-RED%20get.jpeg?raw=true)

<p>Debug Node-Red</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/3.%20Debug%20Node-RED%20get.jpeg?raw=true)

<h1>Metode POST</h1>
<p>Source Code</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Penjelasan%20Kode%20post.jpeg?raw=true)


<p>Flow Chart</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/1.%20Flow%20Chart%20program%20ESP32%20post.png?raw=true)

<p>Flow Chart Program</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Flow%20Program%20post.jpeg?raw=true)


<p>Tabel Database MySQL </p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/5.%20Tabel%20database%20MySQL.jpeg?raw=true)


<p>Output Serial monitor</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/2.%20Output%20serial%20monitor%20post.jpeg?raw=true)

<p>Dashboard Node-Red </p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/4.%20Dashboard%20Node-RED%20post.jpeg?raw=true)

<p>Debug Node-Red</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/3.%20Debug%20Node-RED%20post.jpeg?raw=true)

<b><p>Analisa</p></b>
<p>Metode GET dan POST adalah dua metode pengiriman data dalam protokol HTTP, dan keduanya memiliki perbedaan utama dalam tujuan penggunaan, keamanan, dan cara data dikirimkan. Metode GET digunakan untuk mengambil data dari server dan mengirimkan parameter melalui URL, sehingga data dapat terlihat di history browser dan logs server. Metode ini cocok untuk permintaan data yang tidak memodifikasi informasi di server. Sebaliknya, metode POST digunakan untuk mengirim data ke server untuk diproses, dan data dikirim melalui badan permintaan HTTP, menjadikannya lebih aman karena tidak terlihat di URL. POST lebih cocok untuk mengirim data sensitif atau permintaan yang dapat mengubah status di server. Perbedaan lainnya termasuk panjang data yang dapat dikirim, kemampuan bookmarking, dan pengaturan cache, yang membuat metode GET dan POST memiliki kegunaan yang berbeda sesuai kebutuhan pengembangan aplikasi web. </p>
<p>Kode pada praktikum mengatur konfigurasi dan mengaitkan perangkat Arduino dengan jaringan WiFi, lalu secara teratur mengirimkan data simulasi dari sensor melalui permintaan HTTP POST ke server yang telah ditetapkan. Kode ini dirancang untuk mensimulasikan pengiriman data sensor banjir ke server yang dapat diakses melalui alamat IP tertentu. Jika terjadi putus koneksi WiFi, sebuah pesan kesalahan akan muncul di Serial Monitor.</p>
