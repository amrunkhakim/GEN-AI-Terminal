# GEN-AI-Terminal

GEN-AI Terminal adalah aplikasi terminal desktop modern yang mengintegrasikan kekuatan kecerdasan buatan (AI) untuk membantu pengguna menjalankan perintah kompleks secara lebih mudah dan efisien. Alih-alih mengetik perintah satu per satu, pengguna cukup menuliskan tujuannya dalam bahasa biasa, dan aplikasi akan secara otomatis membuat, menjelaskan, dan menjalankan rencana eksekusi langkah demi langkah.

Aplikasi ini dirancang untuk developer, sysadmin, atau siapa pun yang sering bekerja dengan command line dan ingin mempercepat alur kerja mereka dengan bantuan AI.

Fitur Utama
Perintah Berbasis Tujuan: Cukup deskripsikan apa yang ingin Anda capai (misalnya, "buat folder proyek baru dan inisialisasi git"), dan AI akan menerjemahkannya menjadi perintah terminal yang dapat dieksekusi.

Rencana Eksekusi Interaktif: AI akan menyusun rencana tugas dalam beberapa langkah. Setiap langkah dijelaskan dengan jelas dan dapat dieksekusi satu per satu oleh pengguna, memberikan kontrol penuh atas prosesnya.

Perbaikan Otomatis: Jika sebuah perintah gagal, aplikasi akan meminta AI untuk menganalisis kesalahan dan membuat rencana perbaikan baru secara otomatis.

Dukungan Multi-Provider: Mudah beralih antara penyedia layanan AI terkemuka seperti Google Gemini dan Groq Llama langsung dari menu pengaturan.

Antarmuka Modern & Multi-Tab: Dibangun dengan antarmuka yang bersih dan mendukung banyak tab, memungkinkan pengguna untuk mengerjakan beberapa tugas secara bersamaan.

Konfigurasi Mudah: Pengaturan API key, model AI, dan tema tampilan dapat dengan mudah dikelola melalui jendela pengaturan yang intuitif.

Cara Kerja
Input Pengguna: Pengguna mengetikkan permintaan atau tujuan dalam bahasa natural pada kolom input.

Generasi Rencana: Aplikasi mengirimkan permintaan tersebut ke model AI yang aktif (Gemini atau Groq) untuk dibuatkan rencana dalam format JSON.

Tampilan Rencana: Rencana yang terdiri dari beberapa langkah (deskripsi dan perintah) ditampilkan di panel "Task Plan".

Eksekusi Terkontrol: Pengguna menekan tombol "Execute" untuk menjalankan setiap langkah. Aplikasi akan menjalankan perintah di terminal, dan pengguna dapat melihat outputnya secara langsung.

Penanganan Kegagalan: Jika terjadi error, aplikasi akan menggunakan konteks error tersebut untuk meminta solusi kepada AI, lalu memperbarui rencana dengan langkah-langkah perbaikan.
