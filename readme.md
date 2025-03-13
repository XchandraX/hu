/explore-nusantara
│── /frontend       # 🖥️ Bagian Frontend (React + Tailwind)
│   ├── /src        # 📁 Kode utama frontend ada di sini
│   │   ├── /components    # 🔹 Kumpulan komponen UI yang bisa dipakai ulang
│   │   │   ├── Navbar.jsx      # 🔹 Navigasi utama website
│   │   │   ├── Footer.jsx      # 🔹 Bagian footer website
│   │   │   ├── Card.jsx        # 🔹 Kartu untuk menampilkan tempat wisata
│   │   ├── /pages         # 📁 Halaman utama website (Home, Detail, About, dll.)
│   │   │   ├── Home.jsx        # 🏠 Halaman utama
│   │   │   ├── Detail.jsx      # 🔍 Halaman detail tempat wisata
│   │   │   ├── About.jsx       # ℹ️  Halaman tentang aplikasi
│   │   ├── /assets        # 📂 Gambar, ikon, dan file statis lainnya
│   │   ├── /styles        # 🎨 File CSS untuk styling dengan Tailwind
│   │   ├── App.jsx        # 🚀 File utama React yang menghubungkan semua halaman
│   │   ├── index.js       # 🔧 File awal yang menjalankan React
│   ├── /dist        # 📂 Hasil build setelah Webpack berjalan (jangan diedit)
│   ├── package.json  # 📦 Daftar semua library yang dipakai di frontend
│   ├── webpack.config.js # ⚙️ Konfigurasi Webpack untuk bundling frontend
│   ├── .gitignore    # 🙈 File yang harus diabaikan oleh Git
│   ├── README.md     # 📜 Dokumentasi proyek

│── /backend        # 🔙 Bagian Backend (Node.js + Hapi.js + MySQL)
│   ├── /src        # 📂 Kode utama backend ada di sini
│   │   ├── /config     # 🔧 Folder untuk konfigurasi penting
│   │   │   ├── db.js        # 🔌 Koneksi ke database MySQL
│   │   │   ├── server.js    # 🚀 Konfigurasi utama server backend
│   │   ├── /routes     # 🔀 Folder untuk API routes (endpoint yang bisa diakses frontend)
│   │   │   ├── wisataRoutes.js  # 🏝️ API untuk data tempat wisata
│   │   │   ├── userRoutes.js    # 👤 API untuk autentikasi pengguna
│   │   ├── /controllers  # 🧠 Logika bisnis API (mengatur cara API bekerja)
│   │   │   ├── wisataController.js # 🔥 Logika untuk data wisata
│   │   │   ├── userController.js   # 🔥 Logika untuk autentikasi pengguna
│   │   ├── /models      # 🗂️ Struktur database dalam bentuk kode
│   │   │   ├── wisataModel.js # 🏝️ Struktur tabel wisata di MySQL
│   │   │   ├── userModel.js   # 👤 Struktur tabel pengguna di MySQL
│   ├── package.json  # 📦 Daftar library backend (Hapi.js, MySQL, dll.)
│   ├── .env         # 🔐 File untuk menyimpan konfigurasi rahasia (database, API key, dll.)
│   ├── .gitignore    # 🙈 File yang harus diabaikan oleh Git

│── /ml             # 🤖 Bagian Machine Learning (Python + Scikit-learn)
│   ├── /models     # 🏗️ Model hasil training disimpan di sini
│   │   ├── wisata_model.pkl  # 📌 Model yang sudah dilatih untuk rekomendasi wisata
│   ├── /notebooks  # 📓 Jupyter Notebook untuk eksperimen ML
│   │   ├── train.ipynb  # 🏋️‍♂️ Notebook untuk melatih model
│   ├── train.py     # 🏋️‍♂️ Skrip Python untuk melatih model
│   ├── predict.py   # 🔮 Skrip untuk memprediksi rekomendasi wisata
│   ├── api.py       # 🌐 API Flask untuk memanggil prediksi dari model ML
│   ├── requirements.txt  # 📜 Daftar library Python yang diperlukan

│── /database       # 🗄️ Folder untuk pengaturan database MySQL
│   ├── schema.sql  # 🏗️ File SQL untuk membuat tabel-tabel database
│   ├── migrate.js  # 🔄 Skrip untuk menjalankan migrasi database otomatis

│── .gitignore      # 🙈 Daftar file & folder yang harus diabaikan oleh Git
│── README.md       # 📜 Dokumentasi lengkap proyek
