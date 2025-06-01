# Tubes1_Kelompok-BOTDFI
I. Penjelasan singkat algoritma greedy yang diimplementasikan
Strategi SuperBot menerapkan stategi Algoritma Greedy dengan pendekatan yang lebih canggih dan seimbang. SuperBot dapat mengevaluasi berbagai faktor secara bersamaan, seperti nilai diamond, jarak, tipe diamond, kapasitas, dan posisi base. Dengan cara ini, keputusan yang diambil oleh bot tetap bersifat greedy-memilih langkah terbaik pada setiap waktu berdasarkan informasi lokal, namun tetap mempertimbangkn dampak jangka pendek dan efesien total. Strategi ini menghindari kelemahan klasik dari greedy yang terlalu sederhana dan berpotensi suboptimal dalam skenario kompleks.

II. Requirement yang harus di-install
1. Node.js (https://nodejs.org/en)
2. Docker desktop (https://www.docker.com/products/docker-desktop/)
3. Yarn
4. npm install --global yarn
5. Download source code (.zip) pada release game engine
6. Python (https://www.python.org/downloads/)
7. Download source code (.zip) pada release bot starter pack

III. Command atau langkah-langkah dalam meng-compile atau build program
1. Download Requirement
2. Download source code (.zip) pada release game engine
3. Extract zip tersebut, lalu masuk ke folder hasil extractnya dan buka terminal
4. Masuk ke root directory dari project
5. install dependencies menggunakan yarn
6. Setup default environment variable dengan menjalan kan script untuk windown .\script\copy-env.bat
7. etup local database (buka aplikasi docker desktop terlebih dahulu, lalu jalankan command berikut di terminal)
docker compose up -d database
8. Lalu jalankan untuk windows .\scripts\setup-db-prisma.bat
9. lalu jalankan build
10. lalu jalankan run
11. Kunjungi localhost melalui http://localhost:8082/.
12. untuk menjalankan bot Download source code (.zip) pada release bot starter pack
13. Extract zip tersebut, lalu masuk ke folder hasil extractnya dan buka terminal
14. Masuk ke root directory dari project
15. Install dependencies menggunakan pip
16. Untuk menjalankan satu bot (pada contoh ini, kita menjalankan satu bot dengan logic yang terdapat pada file game/logic/random.py)
17. Untuk menjalankan beberapa bot sekaligus jalankan ./run-bots.bat pada terminal

IV. Author
Fanisa Aulia Safitri(123140121)
Danar Prayogo(123140015)
Ilyas Ramadhan(123140016)
