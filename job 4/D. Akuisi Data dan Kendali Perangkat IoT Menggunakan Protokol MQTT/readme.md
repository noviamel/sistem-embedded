<h1>C. Akuisi Data dan Kendali Perangkat IoT Menggunakan Protokol MQTT</h1>
<b><p>Alat dan Bahan</p></b>
<p>1. ESP 32</p>
<p>2. XAMPP</p>
<p>3. Node-Red</p>
<p>4. Laman Adafruit</p>
<p>5. Jumper</p>
<p>6. LED</p>
<p>7. Protoboard</p>
<br></br>
<b><p>Source Code</p></b>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Penjelasan%20Kode%20d.jpeg?raw=true)

<b><p>Flow Chart</p></b>

<img src="https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/flowchart%20d.png" width="800">


<b><p>Hasil Percobaan Kontrol Nyala LED melalui Dashboar Node-RED </p></b>

<p>Flow Program</p>

 <img src="https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/flow%20program%201.png" width="300">

<p>Dokumentasi</p>

 ![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/2.%20Dokumentasi%201.jpeg?raw=true)

<p>Debug Node-RED</p>

   ![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/3.%20Debug%20Node-RED%20d.jpeg?raw=true)

<p>Dashboard Node-RED</p>

 <img src="https://github.com/brianrahma/system-embedded/blob/master/jobsheet%204/D.%20Akuisi%20Data%20dan%20Kendali%20Perangkat%20IoT%20Menggunakan%20Protokol%20MQTT/dashboard1.png" width="700">

<b><p>Hasil Percobaan Kontrol Nyala LED melalui Dashboar Adafruit  </p></b>

<p>Flow Program</p>

 <img src="https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/flow%20program%202.png" width="500">

 <p>Dokumentasi</p>

  ![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/2.%20Dokumentasi%202.jpeg?raw=true)

  <p>Widget On/Off Adafruit</p>

   ![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/2.%20Dokumentasi.mp4?raw=true)
   
<b><p>Analisa</p></b>
<p>Kode ini mengimpor sejumlah pustaka yang diperlukan, termasuk pustaka WiFi dan pustaka MQTT dari Adafruit. Fungsinya adalah sebagai implementasi untuk menyambungkan perangkat ESP8266 dengan protokol MQTT (Message Queuing Telemetry Transport) ke server Adafruit IO. Program juga mengurus penanganan pesan yang diterima dari topik MQTT 'led'. Jika pesan yang diterima merupakan "1", maka pin keluaran akan diaktifkan (HIGH); sebaliknya, jika tidak sesuai dengan "1", pin keluaran akan dimatikan (LOW). Dilakukan pemeriksaan untuk memastikan bahwa koneksi ke server MQTT telah terbentuk. Jika belum, program akan mencoba melakukan koneksi ulang dengan interval 5 detik pada setiap upaya.</p>
