Tutorial lengkap beserta gambar ada di Tutorial Tugas Docker Compose

Pertama - tama kita buat dulu sebuah folder, misal namanya Docker. Lokasi folder Docker ini saya letakkan di direktori Documents
Lalu kita buka terminal (di windows kalian bisa gunakan Docker Toolbox) dan kita masuk ke direktori folder yang telah kita buat tadi bernama Docker di Downloads dengan cara : cd Documents/Docker
Seperti yang terlihat di atas saya telah masuk ke direktori Documents/Docker. Saya mengetikkan perintah ls untuk melihat isi dari folder Docker yaitu ada docker-compose.yml lalu folder index dan file site.conf.
Kita ketikkan perintah docker images untuk melihat apa saja images yang sudah kita build
Lalu kita lakukan docker compose dengan mengetik perintah docker-compose up -d
Kita cek di browser apakah sudah berhasil kita up docker composenya dengan mengetik ip docker di browser kita  192.168.99.100:8080. Ip dapat kita cek menggunakan (ifconfig untuk linux dan di windows biasanya ada di awal saat menjalankan docker toolbox) dan 8080 adalah port public yang kita set di docker-compose.yml tadi
Selesai
