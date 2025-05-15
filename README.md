### a. AMQP itu apa?

AMQP adalah protokol standar yang digunakan untuk mengatur pengiriman pesan antar aplikasi melalui perantara yang disebut message broker, seperti RabbitMQ. Dengan AMQP, aplikasi bisa saling bertukar pesan secara terstruktur, aman, dan tidak harus terhubung langsung secara real-time. Biasanya digunakan di sistem yang berbasis event-driven atau microservices.

### b. Apa arti dari `amqp://guest:guest@localhost:5672`?

* **guest (pertama):** username untuk login ke RabbitMQ.
* **guest (kedua):** password dari username.
* **localhost:** menunjukkan bahwa server RabbitMQ berjalan di komputer lokal.
* **5672:** port default yang dipakai AMQP.

Jadi, alamat tersebut digunakan untuk menghubungkan aplikasi ke server RabbitMQ lokal menggunakan akun default (guest/guest) melalui port 5672.

