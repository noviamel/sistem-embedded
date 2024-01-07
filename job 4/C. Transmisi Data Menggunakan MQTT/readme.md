<h1>C. Transmisi Data Menggunakan Protokol MQTT</h1>
<b><p>Alat dan Bahan</p></b>
<p>1. ESP 32</p>
<p>2. XAMPP</p>
<p>3. Node-Red</p>
<br></br>
<b><p>Source Code</p></b>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Penjelasan%20Kode%204c.jpeg?raw=true)

<b><p>Flow Chart</p></b>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/Flow%20Chart%204c.png?raw=true)

<b><p>Hasil dan Pembahasan</p></b>
<p>Output serial monitor </p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/2.%20Output%20serial%20monitor%204c.jpeg?raw=true)

<p>Debug Node-RED</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/3.%20Debug%20Node-RED%204c.jpeg?raw=true)

<p>Dashboard Node-RED</p>

![alt text](https://github.com/noviamel/sistem-embedded/blob/main/job%204/media/4.%20Dashboard%20Node-RED%204c.jpeg?raw=true)

<b><p>Analisa</p></b>
<p>Transmisi data menggunakan protokol MQTT (Message Queuing Telemetry Transport) merupakan pendekatan yang efisien dan ringan untuk komunikasi antar perangkat IoT (Internet of Things). Protokol ini dirancang untuk situasi di mana perangkat memiliki keterbatasan daya atau bandwidth, sehingga sangat cocok untuk lingkungan yang memerlukan pertukaran data yang efisien. MQTT bekerja berdasarkan konsep "publish-subscribe", di mana perangkat dapat bertindak sebagai pengirim atau penerima pesan. Perangkat yang ingin mengirim data (publisher) mengirimkan pesan ke suatu topik (topic), dan perangkat yang tertarik (subscriber) dapat berlangganan pada topik tersebut untuk menerima pembaruan. Keunggulan MQTT terletak pada kecepatan dan efisiensinya, serta kemampuan untuk mendukung skenario konektivitas yang tidak stabil. Data dikirimkan dalam bentuk pesan ringan yang dapat dengan cepat disebarkan ke perangkat yang relevan, membuat MQTT menjadi pilihan populer dalam implementasi sistem IoT.</p>
<p>Program ini menggunakan tiga pustaka, yaitu WiFi untuk koneksi Wi-Fi, PubSubClient untuk koneksi MQTT, dan ArduinoJson untuk memanipulasi data dalam format JSON. Selanjutnya, program melakukan inisialisasi terhadap berbagai variabel yang akan digunakan, seperti SSID dan kata sandi untuk mengakses jaringan Wi-Fi, serta alamat server MQTT. Proses berikutnya dalam program adalah mencoba untuk terhubung ke jaringan Wi-Fi dengan menggunakan SSID dan kata sandi yang telah ditetapkan sebelumnya. Data yang akan dikirim dalam format JSON melibatkan identifikasi perangkat (dev_id), tingkat (level), jumlah hujan (rainfall), dan laju aliran (flow). Kontennya mungkin merepresentasikan informasi dari suatu perangkat atau sensor yang terkait dengan manajemen air pintar. Sebagai contoh, dev_id dapat berupa identifikasi unik perangkat, level dapat mengindikasikan tinggi air, rainfall dapat menunjukkan jumlah hujan, dan flow mungkin mencerminkan laju aliran air.</p>
