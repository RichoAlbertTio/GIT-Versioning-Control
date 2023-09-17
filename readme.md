# 1. git init
#    Perintah yang digunakan untuk memulai repositori Git baru di dalam direktori 


# 2. git status
#    Perintah yang digunakan untuk melihat perubahan pada repositori yang dibuat


# 3. git add readme.md
#    Perintah yang digunakan untuk memasukan satu file dalam repositori
#    Kemudian git status untuk melihat perubahannya (git add data/script.js)
#    jika ingin memasukan semua file atau folder kita gunakan "git add ." atau "git add *"


# 4. git commit -m "Menambahkan Folder data/script.js dan readme.md"
#    Perintah yang digunakan untuk menyimpan snapshot (commit) dari perubahan 
#    jadi setiap perubahan memiliki catatan perubahan atau komentar
#    -m menandakan masih beradar pada branch master

# 5. git log atau git log --oneline
#    Perintah yang digunakan untuk melihat history commit perubahan


# 6. a. Masuk ke web github bikin new repositori, buat namanya proyek yang ingin dibuat
#    b. pilih instruksi public jika ingin orang lain bisa melihatnya, dan private hanya orang khusus atau  kita sendiri yang dapat melihatnya
#    c. klik new


# 7. git add remote origin https://github.com/RichoAlbertTio/GIT-Versioning-Control.git
#    git remote add origin https://github.com/RichoAlbertTio/GIT-Versioning-Control.git
#    origin merupakan nama remote, biasanya dikasih nama origin
#    Perintah yang digunakan untuk menghubungkan git lokal pc ke github
#    dengan perintah "git add remote origin" 
#    salin kode ssh "https://github.com/RichoAlbertTio/GIT-Versioning-Control.git"


# 8. git remote -v
#    Perintah yang digunakan untuk mengecek remote


# 9. git push origin master
#    opsional (git push -u origin master)
#    Perintah untuk memasukan data / file ke dalam branch master


# 10. 