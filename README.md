Cara Install dan menjalankan Vue 3 (Vite)

1. install node js
   sudo apt install nodejs

   check version: node -v atau node --version

2. install npm :
   sudo apt install npm

   check version npm -v atau npm --version

3. buat project
   npm create vite@4.2.0 namaprojeknya -- --template vue

   contoh: npm create vite@4.2.0 vue3-crud -- --template vue

4. masuk ke projectnya, 
    cd vue3-crud lalu jalankan:
    npm install untuk mengunduh beberapa dependency yg dibutuhkan

5. jalankan projectnya:
    npm run dev

Install dan Konfigurasi Router di Vue 3

1. install vue router
    npm install vue-router@4.1.6 (krna menggunakan Vue 3 maka instal vue router versi 4 keatas)

2. Integrasi Bootstrap di Vue 3
    Disini kita akan melakukan integrasi Bootstrap di dalam project Vue 3. Dan untuk Bootstrap akan kita ambil dari CDN
    atau Content Delivery Network (Online).

3. Membuat Views
    *buat folder baru dengan nama "views" dan file bernama "home.vue"
       ->buat folder baru lg dgn nama "posts" didalam folder "views" dan file bernama "index.vue"
       ->buat folder baru lg dgn nama "posts" didalam folder "views" dan file bernama "create.vue"
       ->buat folder baru lg dgn nama "posts" didalam folder "views" dan file bernama "edit.vue"

4. Membuat Konfigurasi Router
    *buat folder baru dgn nama "router" dan file bernama "index.js"

5. Register Route
6. Konfigurasi Router View
7. Uji Coba Project


menampilkan data dari Rest API di Vue 3

1. jalankan project laravelnya dlu di local
2. installasi Axios
   npm install axios@1.3.4
3. konfigurasi endpoint api
4. menampilkan data dari rest api di vue 3
    
    
    

