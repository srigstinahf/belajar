## COMMAND DASAR LINUX

## mkdir
mkdir : nambahin folder

- contoh:di dalam terminal ketik mkdir belajar yang nantinya akan langsung terbuat folder "belajar"

## cd
cd : masuk ke dalam folder

- contoh: cd belajar sehingga tampilan pada terminal belajar git(main). artinya itu sudah masuk ke dalam folder tersebut

## touch
touch : nambah new file kosong

- contoh: touch index.html, command tersebut akan membuat sebuah file yang tidak berisi dengan nama index.html 

## cd ..
cd .. : kembali ke folder awal misalnya sebelumnya masuk ke dalam konten folder menggunakan perintah tersebut untuk kembali ke awal

## ls
ls : menampilkan isi konten folder yang ada

- contoh: ketika berada di dalam folder "belajar" di terminal ketika diketikkan ls akan tercantum isi konten folder tersebut seperti pert1, pert2

## rmdir
rmdir: menghapus folder yang kosong (jika ada isinya tidak bisa di hapus)

- contoh: rmdir belajar, perlu diingat lagi bahwa command tersebut hanya digunakan ketika isi folder kosong

## rm
rm -rf "nama isi konten folder'' : menghapus file atau folder berserta isi

- contoh: rm -rf belajar, dalam command ini harus berhati-hati dan yakin karena command ini akan menghapus semua folder berserta isinya

## ping
ping : memeriksa konektivitas jaringan sistem

## mv
mv: untuk memindah file atau rename file

- contoh memindah file: mv src

- contoh rename file: mv src src1

## nano
nano: mengedit teks di terminal (hanya bisa digunakan dalam terminal)

- contoh: nano /root/.zshrc 

## &&
&& : untuk menjalankan dua command atau lebih

- contohnya: mkdir belajar && cd belajar && touch index.html
command tersebut meliputi membuat folder lalu masuk ke dalam folder dan membuat file baru kosong

## CARA RUNNING 
- g++ samplearray.cpp -o samplearray
- ./samplearray


## PUSH KE GITHUB
git init
git add .
git commit -m "pesan" bisa "belajar" atau yang lainnya 
git push -u origin main 

## perubahan pada github
git add .
git commit -m "pesan" bisa "belajar" atau yang lainnya 
git push -u origin main 