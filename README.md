# Belajar-remote
Belajar menggunakan remote di git

* Git clone = mindahin dari GitHub ke perangkat local
 
 salin link HTTPS di bagian code
 ketik di git bash https://github.com/( Username github ) / ( Nama repo ).git


* Dibawah adalah cara mengpublish repo local ke GitHub :

  ( sebelum itu, pastikan buat repo baru dengan nama yang sama seperti di local )

  setelah itu ketik di git bash :
  - git remote add origin https://github.com/( Username GitHub )/( nama repo ).git
  - git branch -M main
  - git push -u origin main

* Cara menambahkan remote :
  - git remote add ( nama remote )

* Cara menghapus remote :
  - git remote remove ( nama remote )

* Jika terjadi conflict saat melakukan push, (keadaan terjadi jika github yang pertama kali melakukan commit) :
  lakukan :
  - git fetch
  - git pull
  
lalu perbaiki kodenya di code editor (ex : visual studio code)

selesai 
NB : Cek status repo dengan mengetik git status untuk mengetahui proses apa yang harus dilakukan agar kode siap untuk di-commit
