**Tutorial Menambahkan SSH KEY,Memebuat Repository dan Upload File Ke Github Menggunakan Gitbash


**

**Latar Belakang :**


Perkembangan teknologi yang semakin pesat membuat orang membutuhkan wadah untuk menyimpan proyek-proyek yang telah dibuat dan bersifat open source agar bisa dilihat oleh semua orang,maka dibuat github yang berfungsi untuk hosting proyek. Melihat kondisi sekarang ternyata github banyak dibutuhkan oleh semua orang,maka disini akan dibuat tutorial atau langkah langkah dalam mengupload file ke hithub serta untuk add ssh key nya.


**Isi**


Github merupakan suatu website yang menyediakan layanan untuk pengembangan web,dimana github ini menggunakan system yang dapat pengontrol git.

Umtuk tutorial ini kita harus mempunyai akun github terlebih dahulu, dan jika telah mmepunyai akun kita bisa langsung login. Apabila kita telah connect dan kita ingin membuat repository sebaiknya kita meng add ssh key terlebih dahulu. Karena fungsi dari ssh key ini adalah untuk pull dan fush.


- Untuk add ssh key,dapat dilihat dari langkah berikut ini :


1. Pertama kita masuk ke Account -&gt;  Setting

2. Kemudian pilih SSH dan  GPS keys


- Untuk membuat Repository baru di github :


1. Pada github klik New Repository

2. Kemudian beri nama pada repository yang akan dibuat

3. Kemudian masukan descripton

4. Lalu pilih Publik dan ceklis initializa this repository with a readme.

5. Klik create Repostitory dan finish.


- Untuk meng-upload file yang format markdown(.md) yang berada di folder doc/kuliah menggunakan GITBASH


1. Masukkan file yang berformat markdown(.md) pada folder doc/kuliah lalu klik Git Bash Here

2. Ketik git init pada gitbash

3. Ketik git remote add origin&quot;Masukan alamat repository&quot; Alamat repository ini di ambil dari github dengan repository yang dibuat sebelumnya lalu klik Clone or Download lalu copy alamat tersebut.

4. Ketik git pull origin master

5. Ketik git status,lalu kita add folder yang akan kita masukan ke github.

6. Ketik add doc/kuliah/pertemuan1.md maka file (.md) tersebut akan masuk ke dalam github.

7. Lalu git status

8. Dan ketik git commit –m &quot;dan masukan komentar &quot;

9. Lalu git push origin master maka file tersebut akan di upload ke dalam repository.


**Kesimpulan :**


Github ini berfungsi sebagai repository git atau pengontrol git dimana github ini bisa dilihat oleh semua orang dan langkah langkah mengupload file di github juga mudah.


**Saran :
**

Sebaiknya jika ingin belajar menggunakan github sebaiknya mencari referseni ataupun tutorial agar memudahkan dalam mempelajarinya.


Referesnsi : [https://id.wikipedia.org/wiki/GitHub](https://id.wikipedia.org/wiki/GitHub)