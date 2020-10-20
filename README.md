# Latihanvcs3

**Nama  :SHOBAHUS SOLICHIN** <br>

**NIM  :312010076** <br>

**KELAS :TI.20.A.1** <br>

## LANGKAH-Langkah Penggunaan Git

*Download git terlebih dahulu,dengan link berikut :[click Here](https://git-scm.com)<br>

![gitscm](foto/gitbash2.png)

*setelah file terdownload silahkan lakukan instalasi dengan 
referensi berikut ini : [Git installation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)<br>

![installing](foto/installing.png)<br>

*setelah installasi selesai,buka**GitBash** pada 
menu di windows, dan lakukan pengecekan **versi**,dengan 
mengetik *syntax* berikut : <br>

`git --version` <br>

![git version](foto/version.PNG) <br>

*jika muncul tampilan **git version**, berarti Git sudah
**berhasil di install** dan bisadi **gunakan** Langkah pertama
kirus **mengkonfirmasikan user name** dan **email di git**,
dengan mengetikan *syntax* berikut : <br>

`git commit --global user.name"masukan nama anda"` <br>

`git commit --global user.email "masukin email anda"` <br>

![Git Config](foto/barugit.PNG)

*buat akun di **GitHub**,seperti contoh dibawah ini. Dan lakukan verifikasi akun melalui 
email yang sudah terdaftar.

*jka akun **GitHub** sudah selesai dibuat dan di verifikasi, proses selanjutnya silahkan buat
Repository sseprti gambar dibawah ini : <br>
**penjelasan**

> * `Repository Name : (Silahkan isi nama repository yan diinginkan seperti contoh saya ingin
membuat repository Latihanvcs3)`<br>

> * `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)`

> * `Public / Private : (Pilih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)` <br>

> * `Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda` <br>

> * `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.` <br>

> * `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan` <br>

![NAMA repositori](foto/Langka1.png)

* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :<br>

![Hasil repository](foto/hasilfile.PNG)

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk *me-remote* repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link *URL git* kita di Github, dengan cara tekan tombol **Code** lalu klik *Copy*.<br>

![Kode link](foto/kode.PNG)

* Setelah *Link URL git kita tercopy*, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan *mendownload* Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih **Git Bash Here**.<br>

![Gitbash](foto/GitBash.png) 

*Pop Up* Command Prompt **(CMD)** akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut :

git clone [URL] pada contohnya, saya akan memasukan git clone
https://github.com/shobahus1/Latihanvcs3.git <br>

![Gitnama](foto/gitnama.PNG)

* Setelah proses cloning selesai, pada saat ini kita masih pada folder awal, kita harus masuk kedalam folder yang telah dicloning tadi yaitu *LatihanVCS* dengan mengetikkan *syntax* berikut :
cd Latihan18/ <br>

![Gitcd](foto/cd.PNG)

* Saat ini kita sudah masuk kedalam folder *LatihanVCS*, Silahkan edit file README.md yang ada di File Explorer. Bisa menggunakan Text Editor *(Sublime Text, Notepad, Notepad++, Visual Studio Code). Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : click here <br>

![Hasilrepository](foto/Readme.png)

Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara **CTRL+S atau File -> Save**

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash **(CMD)**. Ketik pada Git Bash seperti berikut ini :

`git add.`

![Gitadd](foto/Gitadd.PNG)

* Setelah selesai melakukan git add . langkah berikutnya kita akan melakukan *commit. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini :
git commit <br>
`"Update README.md"`

![Gitcommit](foto/gitnama.PNG)

* Git commit telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, Git Push berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut :
git push <br>

![Gitpush](foto/gitpush.PNG)

* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yang telah di *commit* dan *push* dari remote.

![hasilrepository](foto/Hasil.PNG)

**Sekian Terima Kasih**
* apabila ada kata kata yang salah dan penulisan saya mohon maaf <br>





