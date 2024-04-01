## COMMAND DASAR LINUX

- mkdir

mkdir : nambahin folder

contoh:di dalam terminal ketik mkdir belajar yang nantinya akan langsung terbuat folder "belajar"

- cd

cd : masuk ke dalam folder

contoh: cd belajar sehingga tampilan pada terminal belajar git(main). artinya itu sudah masuk ke dalam folder tersebut

- touch

touch : nambah new file kosong

contoh: touch index.html, command tersebut akan membuat sebuah file yang tidak berisi dengan nama index.html 

- cd ..

cd .. : kembali ke folder awal misalnya sebelumnya masuk ke dalam konten folder menggunakan perintah tersebut untuk kembali ke awal

- ls

ls : menampilkan isi konten folder yang ada

contoh: ketika berada di dalam folder "belajar" di terminal ketika diketikkan ls akan tercantum isi konten folder tersebut seperti pert1, pert2

- rmdir

rmdir: menghapus folder yang kosong (jika ada isinya tidak bisa di hapus)

contoh: rmdir belajar, perlu diingat lagi bahwa command tersebut hanya digunakan ketika isi folder kosong

- rm

rm -rf "nama isi konten folder'' : menghapus file atau folder berserta isi

contoh: rm -rf belajar, dalam command ini harus berhati-hati dan yakin karena command ini akan menghapus semua folder berserta isinya

- ping

ping : memeriksa konektivitas jaringan sistem

- mv

mv: untuk memindah file atau rename file

contoh memindah file: mv src

contoh rename file: mv src src1

- nano

nano: mengedit teks di terminal (hanya bisa digunakan dalam terminal)

contoh: nano /root/.zshrc 

- &&

&& : untuk menjalankan dua command atau lebih

contohnya: mkdir belajar && cd belajar && touch index.html
command tersebut meliputi membuat folder lalu masuk ke dalam folder dan membuat file baru kosong

- clear 

clear: untuk menghapus seluruh tampilan program linux yang sedang dijalankan

- cp

cp: untuk menyalin file atau direktori dari satu lokasi ke lokasi lain. Dalam menggunakan perintah ini harus disertai dengan path file awal sumber dan juga tujuan path baru

contoh: cp /home/user/documents/test1.txt /home/user/backups

- sudo

menjalankan perintah sebagai super user. sudo berfungsi untuk menjalankan perintah dengan izin administratif atau root.

- chmod

chmod: untuk mengubah izin direktori atau file di linux.

- ps

ps: untuk membuat snapshot dari semua proses yang sedang berjalan di sistem. Apabila perintah ini dijalankan tanpa opsi atau argumen, outputnya akan menunjukkan proses yang sedang berjalan di shell dengan informasi berikut:
1. ID proses unik (PID).
2. Jenis terminal (TTY).
3. Durasi berjalan (TIME).
4. Perintah yang memulai proses (CMD).

## TAMBAHAN
1. Ketikkan "exit" untuk menutup terminal
2. Tekan ctrl + c untuk menghentikan perintah yang sedang berjalan
3. Ketikkan "clear" untuk menghapus seluruh tampilan program linux yang sedang dijalankan
4. Tekan ctrl + z untuk menjeda perintah yang sedang berjalan
5. Jika ingin memisahkan perintah yang ingin jalan 2 atau lebih 2 bisa menggunakan && atau (;)
6. Tekan ctrl + A untuk pindah ke baris awal
7. Tekan ctrl + E untuk pindah ke baris akhir

## CARA MENAMBAHKAN FOLDER dan FILE DARI TERMINAL
1. Ketik mkdir di terminal, misal mkdir belajar
2. Masuk ke dalam folder belajar menggunakan command "cd", jadi cd belajar
3. Lalu buat folder lagi misal folder pert1 dengab command "mkdir pert1" dan masuk dengan command "cd pert1"
3. Membuat file kosong dengan command "touch", misal touch index.html
4. Untuk menampilkan isi folder bisa ketik command "ls" yang nantinya jika file tersebut sudah dibuat maka nama file tersebut akan tampil
5. Untuk lihat di vscode maka lakukan perintah "cd .." lebih dulu yang nantinya akan kembali ke awal folder, misal sedang menjalankan di folder pert1 ketik di "cd .." maka akan kembali ke folder belajar
6. Setelah sudah ada di folder belajar, ketik "code ." secara otomatis akan masuk ke dalam vscode dan ke dalam folder belajar

## CARA RUNNING SEBUAH FILE
contoh
- g++ samplearray.cpp -o samplearray
- ./samplearray


## PUSH KE GITHUB
- buat new repository di github
- git init
- git add .
- git commit -m "pesan" bisa "belajar" atau yang lainnya 
- git branch -M main 
- git remote ssh (link repository)
- git push -u origini main

## PERUBAHAN PADA GITHUB
- git add .
- git commit -m "pesan" bisa "belajar" atau yang lainnya 
- git push -u origin main 

## catatan kecil
Di Linux, setiap file dikaitkan dengan tiga tingkatan user:owner (permilik), group member (anggota group), dan others (lainnya).

User juga memiliki tiga izin antara lain read (baca), write (tulis), dan execute (jalankan).