**LAPORAN PRAKTIKUM** <br>

========================= <br>
NIM    : 244107027008  <br>
NAMA   : FRANKIE STEINLIE  <br>
KELAS  : TI - 4K RPL  <br>
=========================  <br>

**1.	Praktikum 1 : Menyiapkan Lingkungan Pengembangan**  <br>
**a.	Jelaskan kegunaan masing-masing dari Git, VS Code dan NodeJS yang telah Anda install pada sesi praktikum ini!**  <br>
_Jawaban :_  <br>
Git berguna sebagai wadah setiap project disimpan, sehingga dapat diakses oleh tim maupun orang lain untuk melakukan Kerjasama dalam mengerjakan suatu project, memudahkan kolaborasi antar personal.
VsCode sebagai texteditor untuk membangun project yang dapat diinstall plugin atau ekstensi untuk memudahkan proses pengerjaan project.  <br>
NodeJs sebagai runtime environment untuk menjalankan kode program javascript, dan bisa juga digunakan untuk membangun backend seperti server web, api, dan layanan real-time lainnya.  <br>
**b.	Buktikan dengan screenshoot yang menunjukkan bahwa masing-masing tools tersebut telah berhasil terinstall di perangkat Anda!**  <br>
_Jawaban :_  <br>
![image](https://github.com/user-attachments/assets/578276b6-4942-4d2e-856f-2f9cda4d0450)  <br> 
Pada gambar diatas, terdapat informasi versi Git 2.46.0, versi vscode 1.96.2, versi nodejs v22.12.0 dan versi npm 10.9.0 yang semuanya sudah terinstall pada device saya.  <br>

**2.	Praktikum 2 : Membuat Proyek Pertama React Menggunakan Next.js**  <br>
**a.	Pada Langkah ke-2, setelah membuat proyek baru menggunakan Next.js, terdapat beberapa istilah yang muncul. Jelaskan istilah tersebut, TypeScript, ESLint, Tailwind CSS, App Router, Import alias dan Turbopack!**  <br>
_Jawaban :_  <br>
TypeScript adalah bahasa pemrograman yang merupakan superset dari JavaScript. Ini menambahkan fitur static typing (penulisan tipe data) ke JavaScript, membantu mendeteksi error lebih awal dan membuat code lebih mudah dimaintain.  <br>
ESLint adalah tools untuk analisis kode statis yang membantu menemukan dan memperbaiki masalah dalam kode JavaScript/TypeScript.  <br>
Tailwind CSS adalah framework CSS yang memungkinkan untuk membangun desain dengan menggabungkan class-class utilitas langsung dalam HTML.  <br>
App Router adalah fitur baru di Next.js 13+ yang menggunakan pendekatan file-system based routing dengan konvensi folder.  <br>
Import alias adalah cara untuk membuat shortcut dalam import path.  <br>
Turbopack adalah bundler JavaScript yang diklaim 10x lebih cepat dari Webpack  <br>
**b.	Apa saja kegunaan folder dan file yang ada pada struktur proyek React yang tampil pada gambar pada tahap percobaan ke-3!**  <br>
_Jawaban :_  <br>
| **Nama Folder/File**        | **Keterangan**                                      |
|----------------------------|---------------------------------------------------|
| `/hello-world`             | Root folder proyek                                |
| `/next`                    | Folder yang berisi file-file build Next.js       |
| `/node_modules`            | Berisi semua package/dependencies yang diinstal  |
| `/public`                  | Folder untuk menyimpan asset statis              |
| `/src/app`                 | Folder utama aplikasi yang menggunakan App Router Next.js |
| `file.svg`                 | Asset SVG untuk icon file                        |
| `globe.svg`                | Asset SVG untuk icon globe/dunia                 |
| `next.svg`                 | Logo Next.js                                     |
| `vercel.svg`               | Logo Vercel                                      |
| `window.svg`               | Asset SVG untuk icon window                      |
| `.gitignore`               | Mengatur file/folder yang tidak perlu di-track Git |
| `eslint.config.mjs`        | Konfigurasi ESLint untuk linting kode            |
| `next-env.d.ts`            | Deklarasi tipe TypeScript untuk Next.js          |
| `next.config.ts`           | Konfigurasi Next.js                              |
| `package-lock.json`        | Lock file untuk versi dependencies npm           |
| `package.json`             | Manifest proyek & daftar dependencies           |
| `postcss.config.mjs`       | Konfigurasi PostCSS (digunakan Tailwind)         |
| `tailwind.config.ts`       | Konfigurasi Tailwind CSS                         |
| `tsconfig.json`            | Konfigurasi TypeScript                           |
| `favicon.ico`              | Icon website yang muncul di tab browser         |
| `globals.css`              | CSS global aplikasi                             |
| `layout.tsx`               | Layout utama aplikasi Next.js                   |
| `page.tsx`                 | Halaman utama/root aplikasi                     |

**c.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>
Proses create project :   <br>
![image](https://github.com/user-attachments/assets/6f008638-5eba-4800-afc8-3b49aeaa18b1)  <br>
Proses Running :  <br>
![image](https://github.com/user-attachments/assets/e29e5fdd-440b-4406-831a-71b361f68754)  <br>
Hasil Running :  <br>
![image](https://github.com/user-attachments/assets/d55d1db4-b4e4-4e16-9828-fdcd9c85d6cf)  <br>

**3.	Praktikum 3 : Menambahkan Komponen React (Button)**  <br>
**a.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>
![image](https://github.com/user-attachments/assets/4dc5acea-cc57-482c-9f0e-9d612ca621ae)  <br>
![image](https://github.com/user-attachments/assets/430b8843-4357-4bba-b3e9-87f7d1b5182f)  <br>
![image](https://github.com/user-attachments/assets/bebce86f-473c-4ac8-84a3-9ac522c026ff)  <br>

**4.	Praktikum 4 : Menulis Markup dengan JSX  <br>
a.	Untuk apakah kegunaan sintaks user.imageUrl?**  <br>
_Jawaban :_  <br>
untuk mengakses properti imageUrl dari sebuah objek user  <br>
**b.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>
![image](https://github.com/user-attachments/assets/acf6869c-ecbf-4c9d-8eb0-e3e7627f8a3a)  <br>
![image](https://github.com/user-attachments/assets/fb9b94ba-1127-49cb-8332-1065c6aa856f)  <br>
![image](https://github.com/user-attachments/assets/711e8673-b968-46f2-9c2e-5e426bc9f3af)  <br>





