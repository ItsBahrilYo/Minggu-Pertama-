<!-- Headings -->
# Hi there, welcome
## TASK 1
### 1.Definisi Devops
<!-- Inline Code Block -->
<p>Devops merupakan gabungan dari 2 kata yaitu Development dan Operation, dimana tugasnya adalah untuk membantu dan memfasilitasi kerjasama antara tim Development dan tim Operation dalam membangun aplikasi. Membantu dan memfasilitasi dalam hal apa? dalam devops ada yang disebut sebagai Devops lifecyle
dimana ada proses plan, code,build, test, release, deploy, operate dan monitor. Proses berikut akan terus berulan-ulang dalam startup lifecycle.   GAMBAR LIFECYCLE</p>

<!-- Images -->
![Markdown Logo](https://pakar.co.id/storage/2017/09/devops-process.png)



### 2. Environment Untuk Server

 <!-- UL -->
* Instalasi VM dengan VMWork Station
<p> VMWork Station digunakan untuk membuat beberapa virtual machine dan menjalankannya</p>

1. Buka VMWork Stationnya dan klik create virtual machine

<!-- Images -->
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/1create_virtual_machine.png?raw=true)

2. Klik Use ISO Image dan klik browser lalu cari dimana kalian menyimpan file iso ubuntu servernya

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/2choose_iso.png?raw=true)

3. Personalisasi VMWare kalian dengan mengisikan nama, username dan password
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/3personalization.png?raw=true)

4. Beri nama VM kalian dan pilih dimana kalian ingin menyimpan file vmnya

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/4where_to_put_vm.png?raw=true)

5. Atur berapa besar disk kalian

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/5disksize.png?raw=true)

6. Pada laman ini menampilkan requirement yang akan digunakan, lalu klik pada Customize Hardware
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/6reviewall.png?raw=true)

7. Disini kita dapat mengkostumisasi memori,prosesor, network adapter dll, klik pada Network Adapter dan pilih Bridge
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/8choosing_bridge.png?raw=true)

8. Setelah setting Network Adaptor lalu klik finish
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_virtual_machine/9reviewall_lagi.png?raw=true)

<!-- UL -->
* Instalasi Ubuntu Server
<p> Kebanyakan server mayoritas menggunakan operating sistem linux dan salah satu distro linux yang dipakai adalah ubuntu </p>

1. Pilih bahasa

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/pilih%20bahasa.png?raw=true)

2. Pilih layout keyboard
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/select-keyboard-2.png?raw=true)

3.Pada halaman ini ditunjukkan kofigurasi network, pilih enp0s3 lalu pilih IPv4

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/network-connections.png?raw=true)

4.Pilih manual untuk merubah IP dinamis menjadi statis
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_144715_563.webp?raw=true)

5.Ip telah berubah menjadi static
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_145247_832.webp?raw=true)

6.Pilih custome storage layout, disini kita akan mengatur storage manual

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_145444_336.webp?raw=true)

7.Pilih freespace lalu pilih GPT dan isi size 1G untuk swap memory
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_150721_157.webp?raw=true)

8.Dan gunakan sisanya untuk ext4

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_150823_368.webp?raw=true)

9. Beri nama server dan username

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_151116_144.webp?raw=true)

10.Pilih Install openSSH server untuk meremote vm dari desktop kalian

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_151335_422.webp?raw=true)

11. Proses build vm

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_151421_473.webp?raw=true)

12. Reboot now
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_160632_177.webp?raw=true)

13. VM berhasil terinstall

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_161026_704.webp?raw=true)

14. Check koneksi ke google.com
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas1/install_vm/IMG_20220823_161204_665.webp?raw=true)

<!-- Horizontal Rule -->

---
___

## TASK 2

### 1. Computer Network
<p> Koneksi 2 komputer atau lebih menggunakan berbagai macam cara dan interface seperti kabel LAN, wifi, fiber optik, bluetooth dll yang bertujuan untuk saling bertukar data.
</p>

<p> Jaringan memiliki beberapa tipe yang pertama ada client-to-server. Jaringan ini koneksinya terpusat dimana beberapa perangkat user terkoneksi internet dan hanya satu server yang menangani layanan.

</p>


![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Client-server-model.svg/1024px-Client-server-model.svg.png)

<p> Ada lagi tipe jaringan yang lain yaitu peer-to-peer. Jaringan ini sangat dinamis dalam pelayanannya karena setiap komputer bertindak sebagai client sekaligus servernya jadi tidak bergantung pada 1 server.

</p>

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/P2P_network.svg/800px-P2P_network.svg.png)

### 2. Perintah Linux
<!-- Task List -->

* ls = directory listing
* ls -a = Formatted listing with didden file
* ls -lt = sorting the formatted listing by time modification
* cd = change to home directory
* pwd = show current working directory
* cat = shows what inside the file
* touch = make a file
* nano/vim = open text editor
* more file = Output the contents of the file
* head file = Output the first 10 lines of the file
* tail file = Output the last 10 lines of hte file
* rm = deleting file
* rmdir = deleting directory
* rm -f = force delete file
* rm -rf = force delete directory
* cp = copy file
* cp -r = copy directory
* mv = move/rename file
* ln -s = create symbolic link to file

### 3. Ganti Ip server lama menjadi ip server baru


1. Masuk pada text editor nano dengan perintah

<!-- Code Blocks -->
```bash
  sudo nano /etc/netplan/00-instaler-config.yaml
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/ganti_ip/Screenshot%20from%202022-08-24%2011-58-25.png?raw=true)

2. Ganti IP addresses 192.168.xx.xx terserah dan sesukamu

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/ganti_ip/Screenshot%20from%202022-08-24%2011-58-56.png?raw=true)

3. Lalu check koneksinya ke google.com

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/ganti_ip/Screenshot%20from%202022-08-24%2011-59-17.png?raw=true)

### 2. Remote Server

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/install_apache2/Screenshot%20from%202022-08-23%2022-06-12.png?raw=true)

### 3. Install Web Server Apache2

1. Lakukan update dan upgrade terlebih dahulu
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/install_apache2/Screenshot%20from%202022-08-23%2022-09-48.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/install_apache2/Screenshot%20from%202022-08-23%2022-35-36.png?raw=true)

2. Install apache2 dengan command

<!-- Code Blocks -->
```bash
  sudo install apache2
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/install_apache2/Screenshot%20from%202022-08-23%2022-36-15.png?raw=true)

3. Proses Instalasi

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/install_apache2/Screenshot%20from%202022-08-23%2022-36-51.png?raw=true)

4. Check web server yang telah terinstal
<!-- Code Blocks -->
```bash
sudo systemctl status apache2
```
5. Web browser check
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/install_apache2/Screenshot%20from%202022-08-24%2014-14-24.png?raw=true)

### 4. Install localtunnel

1. Install localtunnel dengan command
<!-- Code Blocks -->
```bash
npm install -g localtunnel
```

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/instalasi_localtunnel/Screenshot%20from%202022-08-24%2014-26-58.png?raw=true)

2. Generate url
<!-- Code Blocks -->
```bash
lt --port 80
```
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/instalasi_localtunnel/Screenshot%20from%202022-08-24%2014-31-26.png?raw=true)

3. Buka url di web browser
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas2/instalasi_localtunnel/Screenshot%20from%202022-08-24%2014-31-40.png?raw=true)


## TASK 3
### 1. Aplikasi
<p>
Merupakan suatu perangkat lunak komputer yang terdiri dari code dan logika-logika pengambilan keputusan yang nantinya mampu menjalankan perintah dari user.
</p>

### 2. Nodejs 

1. Instalasi express

<!-- Code Blocks -->
```bash
exec bash
nvm install 16
npm install express --save
```

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/opennodejs/Screenshot%20from%202022-08-24%2014-37-49.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/opennodejs/Screenshot%20from%202022-08-24%2014-39-20.png?raw=true)


2. Edit index.js
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/opennodejs/Screenshot%20from%202022-08-24%2014-41-23.png?raw=true)


3. Eksekusi dengan perintah node

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/opennodejs/Screenshot%20from%202022-08-24%2014-42-15.png?raw=true)

4. Check hasil di web browser
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/opennodejs/Screenshot%20from%202022-08-24%2016-37-02.png?raw=true)


### Golang
1. Instal golang terlebih dahulu
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/golang/Screenshot%20from%202022-08-24%2022-14-11.png?raw=true)

2. Buat file .go
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/golang/Screenshot%20from%202022-08-24%2023-21-13.png?raw=true)

3. Check aplikasi 
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/golang/Screenshot%20from%202022-08-24%2023-22-40.png?raw=true)

### Python

1. Install pip

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/python/Screenshot%20from%202022-08-24%2023-40-05.png?raw=true)

2. Install flask

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/python/Screenshot%20from%202022-08-24%2023-43-30.png?raw=true)

3. Check di web server local
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tugas3/python/Screenshot%20from%202022-08-24%2023-44-03.png?raw=true)


## TASK 4

### 1. GIT
<p>
adalah sebuah version control sistem (vcs) yg bertugas untuk mencatat perubahan seluruh file atau repository dari sebuah project. Dimana semua orang dapat berkontribusi dan berkolaborasi dalam lingkup open source project yg telah dibuat
</p>

## 2. Buat 3 Repositori (js, go, py)

1. Buat repository di github
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-11-14.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2018-00-13.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2018-04-36.png?raw=true)

2. setting ssh-keygen

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-33-26.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-34-39.png?raw=true)

Lalu pergi ke dasboard github dan klik setting

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-35-07.png?raw=true)

Pada sisi kiri klik SSH and GPG keys

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-35-14.png?raw=true)

Paste public key tadi pada kolom key , dan beri nama key nya

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-47-48.png?raw=true)

key sudah dibuat
![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-48-00.png?raw=true)

3. git add, commit dan push 

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-40-41.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2017-42-46.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2018-02-28.png?raw=true)


![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/Screenshot%20from%202022-08-25%2018-05-44.png?raw=true)

4. dev, stag dan pro branch di masing" repository

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/branch.png?raw=true)

5. Hasil push aplikasi

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/1.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/2.png?raw=true)

![Markdown Logo](https://github.com/ItsBahrilYo/Minggu-Pertama-/blob/master/foto/tuggas4/Github/3.png?raw=true)