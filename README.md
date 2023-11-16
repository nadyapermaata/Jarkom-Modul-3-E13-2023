# Jarkom-Modul-3-E13-2023

| No | Nama | NRP |
|----------|----------|----------|
| 1 | Nadya Permata Sari | 5025201015 |
| 2 | Najma Ulya Agustina | 5025211239 |

<h2>Daftar Isi</h2>

| Soal | Solusi | Testing |
|----------|----------|----------|
| [Soal 1](#soal-1) | [Solusi](#solusi1) | [Testing](#testing1) |
| [Soal 2](#soal-2) | [Solusi](#solusi2) | [Testing](#testing2) |
| [Soal 3](#soal-3) | [Solusi](#solusi3) | [Testing](#testing3) |
| [Soal 4](#soal-4) | [Solusi](#solusi4) | [Testing](#testing4) |
| [Soal 5](#soal-5) | [Solusi](#solusi5) | [Testing](#testing5) |
| [Soal 6](#soal-6) | [Solusi](#solusi6) | [Testing](#testing6) |
| [Soal 7](#soal-7) | [Solusi](#solusi7) | [Testing](#testing7) |
| [Soal 8](#soal-8) | [Solusi](#solusi8) | [Testing](#testing8) |
| [Soal 9](#soal-9) | [Solusi](#solusi9) | [Testing](#testing9) |
| [Soal 10](#soal-10) | [Solusi](#solusi10) | [Testing](#testing10) |
| [Soal 11](#soal-11) | [Solusi](#solusi11) | [Testing](#testing11) |
| [Soal 12](#soal-12) | [Solusi](#solusi12) | [Testing](#testing12) |
| [Soal 13](#soal-13) | [Solusi](#solusi13) | [Testing](#testing13) |
| [Soal 14](#soal-14) | [Solusi](#solusi14) | [Testing](#testing14) |
| [Soal 15](#soal-15) | [Solusi](#solusi15) | [Testing](#testing15) |
| [Soal 16](#soal-16) | [Solusi](#solusi16) | [Testing](#testing16) |
| [Soal 17](#soal-17) | [Solusi](#solusi17) | [Testing](#testing17) |
| [Soal 18](#soal-18) | [Solusi](#solusi18) | [Testing](#testing18) |
| [Soal 19](#soal-19) | [Solusi](#solusi19) | [Testing](#testing19) |
| [Soal 20](#soal-20) | [Solusi](#solusi20) | [Testing](#testing20) |

Prefix IP Kelompok E13: 10.43

Soal:
Perjalanan selanjutnya akan menggunakan peta berikut:

<img width="470" alt="soal1" src="images/2.png">

dengan ketentuan sebagai berikut:

| Node | Kategori | Image Docker |  Konfigurasi IP |
|----------|----------|----------| ----------|
| Aura | Router (DHCP Relay) | danielcristh0/debian-buster:1.1 | Dynamic |
| Himmel | DHCP Server |  danielcristh0/debian-buster:1.1 | Static |
| Heiter | DNS Server |  danielcristh0/debian-buster:1.1 | Static |
| Denken | Database Server | danielcristh0/debian-buster:1.1 | Static |
| Eisen | Load Balancer | danielcristh0/debian-buster:1.1 | Static |
| Frieren | Laravel Worker |  danielcristh0/debian-buster:1.1 | Static |
| Flamme | Laravel Worker |  danielcristh0/debian-buster:1.1 | Static |
| Fern | Laravel Worker | danielcristh0/debian-buster:1.1 | Static |
| Lawine| PHP Worker | danielcristh0/debian-buster:1.1 | Static |
| Linie| PHP Worker | danielcristh0/debian-buster:1.1 | Static |
| Lugner |PHP Worker |  danielcristh0/debian-buster:1.1 | Static |
| Revolte| Client | danielcristh0/debian-buster:1.1 | Dynamic |
| Ritcher | Client | danielcristh0/debian-buster:1.1 | Dynamic |
| Sein | Client | danielcristh0/debian-buster:1.1 | Dynamic |
| Stark | Client |  danielcristh0/debian-buster:1.1 | Dynamic |


Setelah mengalahkan Demon King, perjalanan berlanjut. Kali ini, kalian diminta untuk melakukan register domain berupa riegel.canyon.yyy.com untuk worker Laravel dan granz.channel.yyy.com untuk worker PHP (0) mengarah pada worker yang memiliki IP [prefix IP].x.1.

<h3>Soal 1</h3>
Lakukan konfigurasi sesuai dengan peta yang sudah diberikan!
<h4>Solusi</h4> <a name="solusi1"></a>
<h4>Testing</h4> <a name="testing1"></a>

Kemudian, karena masih banyak spell yang harus dikumpulkan, bantulah para petualang untuk memenuhi kriteria berikut.:

<h3>Soal 2</h3>
Semua CLIENT harus menggunakan konfigurasi dari DHCP Server.
Client yang melalui Switch3 mendapatkan range IP dari [prefix IP].3.16 - [prefix IP].3.32 dan [prefix IP].3.64 - [prefix IP].3.80 

<h4>Solusi</h4> <a name="solusi2"></a>
<h4>Testing</h4> <a name="testing2"></a>

<h3>Soal 3</h3>
Client yang melalui Switch4 mendapatkan range IP dari [prefix IP].4.12 - [prefix IP].4.20 dan [prefix IP].4.160 - [prefix IP].4.168

<h4>Solusi</h4> <a name="solusi3"></a>
<h4>Testing</h4> <a name="testing3"></a>

<h3>Soal 4</h3>
Client mendapatkan DNS dari Heiter dan dapat terhubung dengan internet melalui DNS tersebut

<h4>Solusi</h4> <a name="solusi4"></a>
<h4>Testing</h4> <a name="testing4"></a>

<h3>Soal 5</h3>
Lama waktu DHCP server meminjamkan alamat IP kepada Client yang melalui Switch3 selama 3 menit sedangkan pada client yang melalui Switch4 selama 12 menit. Dengan waktu maksimal dialokasikan untuk peminjaman alamat IP selama 96 menit 

<h4>Solusi</h4> <a name="solusi5"></a>
<h4>Testing</h4> <a name="testing5"></a>

Berjalannya waktu, petualang diminta untuk melakukan deployment.

<h3>Soal 6</h3>
Pada masing-masing worker PHP, lakukan konfigurasi virtual host untuk website berikut dengan menggunakan php 7.3

<h4>Solusi</h4> <a name="solusi6"></a>
<h4>Testing</h4> <a name="testing6"></a>

<h3>Soal 7</h3>
Kepala suku dari Bredt Region memberikan resource server sebagai berikut:

- Lawine, 4GB, 2vCPU, dan 80 GB SSD.
- Linie, 2GB, 2vCPU, dan 50 GB SSD.
- Lugner 1GB, 1vCPU, dan 25 GB SSD.
  
aturlah agar Eisen dapat bekerja dengan maksimal, lalu lakukan testing dengan 1000 request dan 100 request/second.

<h4>Solusi</h4> <a name="solusi7"></a>
<h4>Testing</h4> <a name="testing7"></a>

<h3>Soal 8</h3>
Karena diminta untuk menuliskan grimoire, buatlah analisis hasil testing dengan 200 request dan 10 request/second masing-masing algoritma Load Balancer dengan ketentuan sebagai berikut:

- Nama Algoritma Load Balancer
- Report hasil testing pada Apache Benchmark
- Grafik request per second untuk masing masing algoritma. 
- Analisis

<h4>Solusi</h4> <a name="solusi8"></a>
<h4>Testing</h4> <a name="testing8"></a>

<h3>Soal 9</h3>
Dengan menggunakan algoritma Round Robin, lakukan testing dengan menggunakan 3 worker, 2 worker, dan 1 worker sebanyak 100 request dengan 10 request/second, kemudian tambahkan grafiknya pada grimoire.

<h4>Solusi</h4> <a name="solusi9"></a>
<h4>Testing</h4> <a name="testing9"></a>

<h3>Soal 10</h3>
Selanjutnya coba tambahkan konfigurasi autentikasi di LB dengan dengan kombinasi username: “netics” dan password: “ajkyyy”, dengan yyy merupakan kode kelompok. Terakhir simpan file “htpasswd” nya di /etc/nginx/rahasisakita/

<h4>Solusi</h4> <a name="solusi10"></a>
<h4>Testing</h4> <a name="testing10"></a>

<h3>Soal 11</h3>
Lalu buat untuk setiap request yang mengandung /its akan di proxy passing menuju halaman https://www.its.ac.id. hint: (proxy_pass)

<h4>Solusi</h4> <a name="solusi11"></a>
<h4>Testing</h4> <a name="testing11"></a>

<h3>Soal 12</h3>
Selanjutnya LB ini hanya boleh diakses oleh client dengan IP [Prefix IP].3.69, [Prefix IP].3.70, [Prefix IP].4.167, dan [Prefix IP].4.168. hint: (fixed in dulu clinetnya)

<h4>Solusi</h4> <a name="solusi12"></a>
<h4>Testing</h4> <a name="testing12"></a>

Karena para petualang kehabisan uang, mereka kembali bekerja untuk mengatur riegel.canyon.yyy.com.

<h3>Soal 13</h3>
Semua data yang diperlukan, diatur pada Denken dan harus dapat diakses oleh Frieren, Flamme, dan Fern!

<h4>Solusi</h4> <a name="solusi13"></a>
<h4>Testing</h4> <a name="testing13"></a>

<h3>Soal 14</h3>
Frieren, Flamme, dan Fern memiliki Riegel Channel sesuai dengan quest guide berikut. Jangan lupa melakukan instalasi PHP8.0 dan Composer
Riegel Channel memiliki beberapa endpoint yang harus ditesting sebanyak 100 request dengan 10 request/second. Tambahkan response dan hasil testing pada grimoire.
POST /auth/register (15)
POST /auth/login (16)
GET /me (17)

<h4>Solusi</h4> <a name="solusi14"></a>
<h4>Testing</h4> <a name="testing14"></a>

<h3>Soal 15</h3>
<h4>Solusi</h4> <a name="solusi15"></a>
<h4>Testing</h4> <a name="testing15"></a>

<h3>Soal 16</h3>
<h4>Solusi</h4> <a name="solusi16"></a>
<h4>Testing</h4> <a name="testing16"></a>

<h3>Soal 17</h3>
<h4>Solusi</h4> <a name="solusi17"></a>
<h4>Testing</h4> <a name="testing17"></a>

<h3>Soal 18</h3>
Untuk memastikan ketiganya bekerja sama secara adil untuk mengatur Riegel Channel maka implementasikan Proxy Bind pada Eisen untuk mengaitkan IP dari Frieren, Flamme, dan Fern.

<h4>Solusi</h4> <a name="solusi18"></a>
<h4>Testing</h4> <a name="testing18"></a>

<h3>Soal 19</h3>
Untuk meningkatkan performa dari Worker, coba implementasikan PHP-FPM pada Frieren, Flamme, dan Fern. Untuk testing kinerja naikkan 
- pm.max_children
- pm.start_servers
- pm.min_spare_servers
- pm.max_spare_servers
sebanyak tiga percobaan dan lakukan testing sebanyak 100 request dengan 10 request/second kemudian berikan hasil analisisnya pada Grimoire.

<h4>Solusi</h4> <a name="solusi19"></a>
<h4>Testing</h4> <a name="testing19"></a>

<h3>Soal 20</h3>
Nampaknya hanya menggunakan PHP-FPM tidak cukup untuk meningkatkan performa dari worker maka implementasikan Least-Conn pada Eisen. Untuk testing kinerja dari worker tersebut dilakukan sebanyak 100 request dengan 10 request/second

<h4>Solusi</h4> <a name="solusi20"></a>
<h4>Testing</h4> <a name="testing20"></a>


