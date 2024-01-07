<h1>A. Setting SSID dan Password Wi-Fi ESP 32 melalui Web Server</h1>
<b><p>Alat dan Bahan</p></b>
<p>1. ESP 32</p>
<p>2. Aplikasi Arduino IDE</p>
<br></br>
<b><p>Source Code</p></b>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Penjelasan%20Kode.jpeg?raw=true)

<b><p>Flow Chart</p></b>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Flow%20Chart.png?raw=true)

<b><p>Hasil dan Pembahasan</p></b>
<p>Serial monitor setelah berhasil terhubung</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/4.%20Serial%20Monitor%20Setelah%20Berhasil%20Terhubung.jpeg?raw=true)

<p>Serial monitor setelah memasukan SSID dan password </p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/3.%20serial%20monitor%20setelah%20memasukan%20ssid%20dan%20pass.jpeg?raw=true)

<b><p>Analisa</p></b>
<p>Perintah yang diberikan berfungsi untuk mengaktifkan hotspot WiFi dengan nama "my-hotspot" dan kata sandi "my-password". Hotspot WiFi ini dapat diakses oleh perangkat lain yang berada di sekitar komputer. Beberapa hotspot WiFi yang terdeteksi di sekitar komputer meliputi: KENTUNGERS, Warung BNR, Redmi, My family, Griya Titi, Aisyah, Bocill, ulistyo-5G. Implementasi kode program ini menggunakan kelas WiFi dan HTTPClient untuk melakukan pengaturan dan mengirim permintaan HTTP. Kelas WiFi digunakan untuk menghubungkan perangkat ke jaringan WiFi, sedangkan kelas HTTPClient digunakan untuk mengirimkan permintaan HTTP ke server.</p>
