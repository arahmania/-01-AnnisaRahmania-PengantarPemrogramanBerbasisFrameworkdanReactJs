Tugas - Pengantar Pemrograman Berbasis Framework dan Reactjs
1.	Praktikum 1 : Menyiapkan Lingkungan Pengembangan
a.	Jelaskan kegunaan masing-masing dari Git, VS Code dan NodeJS yang telah Anda install pada sesi praktikum ini!
Jawaban:
Git merupakan wadah untuk menyimpan projek yang dapat dikelola secara individu maupun bersama dalam suatu tim, kolaborasi pada tim dapat mempermudah dalam pembuatan suatu projek
VS Code merupakan sebuah text editor yang digunakan untuk membangun projek yang plugin plugin yang dapat mempermudah dalam proses pembangunan projek
NodeJS merupakan runtime yang berjalan di server berfungsi untuk menjalankan kode program javascript. Nodejs juga dapat digunakan untuk backend API dan layanan realtime lainnya
b.	Buktikan dengan screenshoot yang menunjukkan bahwa masing-masing tools tersebut telah berhasil terinstall di perangkat Anda!
Jawaban :
 ![image](https://github.com/user-attachments/assets/6b5a62ee-80e7-4faa-8240-a139ac519637)

Pada hasil diatas terdapat informasi Git versi 2.42.0 , vscode versi 0.44.9 , nodejs versi v18.18.0 dan versi npm 9.8.1 yang sudah terinstall pada device.
 
2.	Praktikum 2 : Membuat Proyek Pertama React Menggunakan Next.js
a.	Pada Langkah ke-2, setelah membuat proyek baru menggunakan Next.js, terdapat beberapa istilah yang muncul. Jelaskan istilah tersebut, TypeScript, ESLint, Tailwind CSS, App Router, Import alias, App router, dan Turbopack!
Jawaban :
TypeScript merupakan superset dari JavaScript yang menambahkan fitur-fitur baru yang tidak ada di JavaScript
ESLint adalah tools untuk analisis yang digunakan untuk membantu/menjaga  kode serta mencegah bug dalam JavaScript dan TypeScript
Tailwind CSS adalah framework CSS berbasis utility-first yang memungkinkan untuk membangun desain dalam html tanpa perlu membuat stylesheet tambahan.
App Router adalah fitur baru di Next.js 13+ yang menggantikan pages/, yang menggunakan pendekatan file-system based routing dengan konvensi folder.
Import alias adalah cara untuk membuat shortcut dalam import path.
Turbopack adalah bundler baru yang dikembangkan oleh Vercel (pembuat Next.js), dirancang untuk menjadi lebih cepat daripada Webpack dan Vite.

b.	Apa saja kegunaan folder dan file yang ada pada struktur proyek React yang tampil pada gambar pada tahap percobaan ke-3!
Jawaban :
Folder/File	Kegunaan
/hello-world	Root folder proyek
/next	Folder yang berisi file-file build Next.js
/node_modules	Berisi semua package/dependencies yang diinstal
/public	Berisi aset statis seperti ikon, gambar, dan file SVG yang bisa diakses langsung.
/src/app	Direktori utama untuk halaman dan layout dalam Next.js 13+
public/file.svg	
Ikon atau gambar yang dapat digunakan dalam aplikasi

public/globe.svg	Ikon globe, mungkin untuk navigasi atau branding
public/next.svg	Logo Next.js 
public/vercel.svg	Logo vercel untuk link deploy di vercel
public/window.svg	Ikon jendela untuk UI atau ilustrasi.
src/app/favicon.ico	Icon website yang muncul di tab browser
src/app/globals.css	CSS global aplikasi
src/app/layout.tsx	struktur tata letak utama aplikasi Next.js
src/app/page.tsx	File utama untuk halaman beranda aplikasi.
.gitignore	Mengatur file/folder yang tidak perlu di-track Git

eslint.config.mjs	Konfigurasi ESLint untuk memastikan kode tetap konsisten dan bebas dari kesalahan.
next-env.d.ts	File deklarasi TypeScript oleh Next.js 
next.config.ts	konfigurasi Next.js untuk mengatur berbagai fitur Next.js
package-lock.json	Lock file untuk versi dependencies npm
package.json	Manifest proyek & daftar dependencies
postcss.config.mjs	Konfigurasi PostCSS (digunakan Tailwind)
README.md	Dokumentasi proyek yang biasanya berisi petunjuk instalasi dan penggunaan
tailwind.config.ts	File konfigurasi Tailwind CSS
tsconfig.json	Konfigurasi TypeScript untuk proyek Next.js.

c.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!
Jawaban :
Proses create project
 
Masuk kedalam folder hello world
 
Proses running
 
Hasil running
 

3.	Praktikum 3 : Menambahkan Komponen React (Button)
Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!
Jawaban :
Menambahkan kode untuk button
 
 
Hasil Perubahan
 
4.	Praktikum 4: Menulis Markup dengan JSX
a.	Untuk apakah kegunaan sintaks user.imageUrl?
Jawaban :
Sintak user.imageUrl digunakan untuk mengakses properti atau atribut yang berisi URL gambar dari objek user
b.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!
