<!-- Headings -->
# Hi there!
## Task CICD with Cloudflare Pages

## 1. Cloudflare Pages
<p>
Merupakan tempat untuk frontend developer mendeploy sebuah aplikasi frontend.
</p>

## 2. Fork repository ke akun github


* Masuk ke akun github anda lalu,
* Buka tab browser baru dan kunjungi https://github.com/dumbwaysdev/wayshub-frontend/tree/main/src lalu klik icon+tulisan fork di pojok kanan atas tampilan github 
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/Screenshot%20from%202022-08-31%2022-16-02.png?raw=true)

* Masuk ke terminal lalu clone project yang telah anda fork di repository anda
<!-- Code Blocks -->
```bash
  git clone <ssh-link repository anda>

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/12.png?raw=true)



## 3. Deploy aplikasi yang sudah difork menggunakan Cloudflare

* Masuk ke akun Cloudflare Pages anda lalu klik pada pages di sebelah kiri dasboard
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/1.png?raw=true)

* Klik connect to Git untuk mengkoneksikan git akun anda
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/2.png?raw=true)

* Pilih akun github anda dan pilih repository yang akan dikoneksikan
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/3.png?raw=true)

* Isi project name sesuai selera, dan pilih production branch anda
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/4.png?raw=true)

* Pilih framework dari aplikasi yang ingin dideploy, pilih build command lalu pilih directory dimana anda ingin menyimpan hasil build. Lalu save & deploy

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/5.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/6.png?raw=true)

* Hasil konfigurasi build & deployment setting

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/7.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/8.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/9.png?raw=true)

* Ini merupakan website yang telah berhasil dijalankan ke server Cloudflare Pages
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/11.png?raw=true)
* Sekarang kita akan melakukan percobaan untuk proses CICD dengan mengubah nama title page. Buka terminal dan pergi ke /wayshub-frontend/public lalu buka file dengan nama index.html denga text editor nano
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/13.png?raw=true)

* Pada kolom title, rubah title sesuai dengan keinginan anda
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/Screenshot%20from%202022-08-31%2023-39-47.png?raw=true)

* Lalu add, commit dan push perubahan ke github anda 
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/15.png?raw=true)

* Cek pada akun cloudflare anda apakah pages project anda berproses terhadap perubahan yang anda lakukan. Seperti yang anda lihat pada pojok kanan bawah pages production anda terlihat 'in progress' ini menandakan bahwa proses CICD telah tercapai.
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-senin/17.png?raw=true)


## Manage Server with Terminal

## 1. Terminal
<p> 
Sebuah command prompt dimana kita bisa mengatur bagaimana suatu sistem komputer berjalan mulai dari management folder, menjalankan dan memberhentikan program serta memonitoring bagaimana sistem komputer berjalan.
</p>

## 2. Keuntungan menguasai terminal

<p> Dengan menguasai bahasa terminal kita bisa mengoperasikan suatu sistem operasi dengan efektif dan effisien
menjalankan, menginstall, menguninstall, memberhentkan cukup di terminal </p>

## 3. Membuat file sederhana untuk update & upgrade sistem

* Buka terminal lalu buat file menggunakan perintah di bawah
<!-- Code Blocks -->
```bash
nano update_upgrade.sh 

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/uu1.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/uu2.png?raw=true)

* Simpan lalu keluar dan eksekusi filenya dengan perintah
<!-- Code Blocks -->
```bash
sh update_upgrade.sh 

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/uu4.png?raw=true)

* File yang sudah dibuat telah tereksekusi dengan baik
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/uu5.png?raw=true)

## 4. Membuat file sederhana untuk membuat firewall port 22, port 80 dan port 443

* Sama seperti cara sebelumnya yaitu buat filenya terlebih dahulu dengan perintah
<!-- Code Blocks -->
```bash
nano update_upgrade.sh 

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/Screenshot%20from%202022-08-30%2015-22-09.png?raw=true)

* Setelah menyimpan dan keluar dari text editoor nano lalu enable firewall dengan perintah
<!-- Code Blocks -->
```bash
sudo ufw enable 

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/Screenshot%20from%202022-08-30%2015-26-35.png?raw=true)

* Lalu eksekusi file yang telah dibuat dengan perintah

<!-- Code Blocks -->
```bash
sh allow_ufw.sh

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-selasa/Screenshot%20from%202022-08-30%2015-27-28.png?raw=true)


## Monitoring

merupakan aktivitas untuk melihit kinerja suatu sistem

* Ada beberapa perintah yang bisa digunakan untuk memonitoring sistem

htop : menampilkan hasil keseluruhan kinerja sistem

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-39-16.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-40-35.png?raw=true)





nmon : menampilkan hasil kinerja sistem secara spesifik
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-41-13.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-41-27.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-41-44.png?raw=true)



![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-41-58.png?raw=true)





lsof : melihat seluruh file yang tebuka berdasarkan proses
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-42-28.png?raw=true)



ps   : melihat suatu proses yang berjalan
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/monitoring/Screenshot%20from%202022-09-02%2006-43-40.png?raw=true)

## Web Server and Load Balancing

## 1. Web Server

<p>
Merupakan server yang menerima request dari user lalu meneruskannya ke database lalu meneruskan hasil request kembali kepada user
</p>

## 2. Membuat 3 buah server (Web server, server aplikasi 1 , server aplikasi 2)

* Pertama-tama buat 2 server dulu untuk mempraktekkan konsep reverse proxy
menggunakan multipass

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/1.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/2.png?raw=true)

* Install web server nginx dengan perintah
<!-- Code Blocks -->
```bash
sudo apt install nginx

```
* Lalu cek web servernya dengan perintah
<!-- Code Blocks -->
```bash
systemctl status nginx

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/3.png?raw=true)

* Buat directory di /etc/nginx untuk file konfigurasi reverse proxy
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/4.png?raw=true)

* Ubah ownership folder tersebut agar kita bisa edit file di dalam folder tersebut dengan perintah
<!-- Code Blocks -->
```bash
sudo chown ubuntu:ubuntu <nama folder>

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/5.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/6.png?raw=true)

* Buat file di dalam folder tersebut lalu buka dengan text editor nano

<!-- Code Blocks -->
```bash
touch <nama file>.conf
nano <nama file>

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/7.png?raw=true)
 
 * Ubah server name dengan domain sesuai selera anda, dan masukkan ip dari server aplikasi anda diikuti dengan port aplikasinya
 ![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/8.png?raw=true)
 * Exit lalu masuk kedalam directory /etc/nginx lalu buka file nginx.conf dengan nano
 <!-- Code Blocks -->
```bash
nano nginx.conf

```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/9.png?raw=true)

* Scroll ke bawah sampain menemukan tulisan include, lalu masukkan directory file dari reverse proxy yang anda buat
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/10.png?raw=true)
* Lalu cek apakah perubahan yang dilakukan berhasil tereksekusi dengan command
<!-- Code Blocks -->
```bash
sudo nginx -t

```
* Restart nginx
<!-- Code Blocks -->
```bash
sudo systemctl restart nginx

```
* Langkah selanjutnya pergi ke lokal komputer anda lalu masuk pada directory /etc/hosts dan buka dengan text editor nano
<!-- Code Blocks -->
```bash
sudo nano /etc/hosts
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/12.png?raw=true)
* Masukkan ip dari server aplikasi dan nama domain yang telah di setting tadi
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/13.png?raw=true)

* Pergi ke server aplikasi dan clone project yang ingin di deploy
dengan perintah

<!-- Code Blocks -->
```bash
git clone <url project>
```

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/14.png?raw=true)

* Pergi ke web browser lalu masukkan domain kalian tadi
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/15.png?raw=true)

* Sebenarnya semua konfigurasi sudah benar, kenapa muncul bad gateway? ya karena kita belum start aplikasinya di server aplikasi
* Sekarang pergi ke server aplikasi lalu install nvm dan npm di directory aplikasinya
<!-- Code Blocks -->
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
exec bash
nvm install 16
npm install
```


![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/16.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/17.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/18.png?raw=true)

* Proses install npm selesai
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/19.png?raw=true)

* Lalu jalankan aplikasi dengan perintah
<!-- Code Blocks -->
```bash
npm start
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/20.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/21.png?raw=true)

* Lalu pergi ke browser dan masukkan domain anda
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/reverseproxy/22.png?raw=true)


## 4.Load Balancing

* Buat server untuk aplikasi dan masuk ke shell
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/1.png?raw=true)
* Install nvm dan npm nya
<!-- Code Blocks -->
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
exec bash
nvm install 16
npm install
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/2.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/3.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/4.png?raw=true)

* Lalu pergi /etc/nginx/dumbflix di web server untuk meng-konfigurasi file reverse_proxy.conf nya dan buka dengan nano
<!-- Code Blocks -->
```bash
nano reverse_proxy.conf
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/5.png?raw=true)

* ubah script di dalam menjadi seperti di gambar

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/6.png?raw=true)

* Keluar dari tex editor nano lalu cek apakah perubahan berhasil dan restart nginx
<!-- Code Blocks -->
```bash
sudo nginx -
sudo systemctl restart nginx
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/7.png?raw=true)
* Pergi ke server aplikasi , masuk ke directory aplikasi lalu jalankan aplikasi dengan perintah
<!-- Code Blocks -->
```bash
npm start
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/8.png?raw=true)
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/9.png?raw=true)

* Kedua server aplikasi berhasil dijalankan
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/10.png?raw=true)

* Sekarang kita akan cek apakah load balancing bekerja dengan cara mematikan salah satu server aplikasi
dengan ctrl+c

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/11.png?raw=true)

* Buka browser dan masukkan domain
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Kedua/blob/master/tugas-rabu/loadbalancing/12.png?raw=true)

* Ternyata masih bisa di buka, load balancing berhasil

