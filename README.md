# PUBG-STEAM-NO-RECOIL-lua-Script-mouse-logitech
Script created by indonesian people!


♣ Script Lua Logitech yang Anda bagikan adalah script anti-recoil tingkat lanjut (advanced) untuk game PUBG. Script ini memiliki fitur kustomisasi lengkap seperti pemilihan jenis senjata, mode scope, hingga opsi untuk triple-shot (atau burst).
Berikut adalah penjelasan lengkap mengenai cara kerja, fungsi tombol, dan cara penggunaannya:

1. Cara Kerja & Logika Tombol (Indikator Keyboard)
Script ini membaca status tombol lampu indikator pada keyboard Anda (Caps Lock, Scroll Lock, dan Num Lock) untuk menentukan profil senjata dan mode yang sedang digunakan:

Pemilihan Senjata (gunmode):

Caps Lock NYALA (On): Mode senjata Beryl M762.
Caps Lock MATI (Off): Mode senjata M416.

Mode Tembak / Burst (triple):
Scroll Lock NYALA (On): Mode Triple/Burst aktif (menggunakan tabel recoil yang lebih tinggi).
Scroll Lock MATI (Off): Mode normal/tap/auto biasa.

Jenis Scope / Attachment (parcali):
Num Lock NYALA (On): Mengaktifkan mode scope tertentu (misalnya asumsi penggunaan scope seperti 3x/6x dengan kompensasi khusus).

Num Lock MATI (Off): Mode scope standar (red dot/holo/tanpa scope khusus).

2. Cara Kerja Script Saat Menembak
Script akan terus berjalan di latar belakang (while true do).

Script baru akan aktif hanya jika Anda menahan Klik Kanan mouse (IsMouseButtonPressed(3))  sama seperti script sebelumnya, ini berfungsi sebagai tombol ADS / Aim.

Saat Klik Kanan ditahan dan Anda mulai menembak dengan Klik Kiri (IsMouseButtonPressed(1)), script akan otomatis menarik kursor mouse ke bawah secara berurutan sesuai dengan tabel angka (recoil_table) yang sudah disiapkan untuk meredam recoil senjata.






♣ BERIKUT CARA PENGINSTALLAN DARI SCRIPT LUA MOUSE LOGITECH
Berikut adalah langkah-langkah mudah untuk memasang dan menginstal script Lua (macro) ke mouse Logitech menggunakan aplikasi resmi Logitech G HUB:

Langkah 1: Persiapan Awal di Logitech G HUB
Buka Aplikasi G HUB: Pastikan mouse Logitech Anda sudah terhubung dan terdeteksi di software Logitech G HUB.

Nonaktifkan On-Board Memory: Pastikan mode memori internal (On-board Memory Mode) dalam keadaan mati (Off). Script Lua tidak dapat berjalan jika mode ini aktif.   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

Atur Profil Desktop:

Masuk ke menu Profiles.   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

Pastikan profil default Anda diset sebagai Desktop (jadikan persistent) agar script dapat berjalan secara mulus.   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

Langkah 2: Membuat dan Memasukkan Script Lua
Klik pada ikon mouse Anda di beranda G HUB, lalu pilih ikon Scripting (biasanya dilambangkan dengan simbol kurung siku {} atau menu Script di sisi kiri/atas tergantung versi G HUB).

Jika belum ada script, klik Create New Script lalu pilih Create a New LUA Script.   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

Memasukkan Kode Script:

Cara 1 (Copy-Paste): Hapus semua teks bawaan di dalam jendela editor script G HUB, lalu copy (salin) kode script Lua yang Anda miliki dan paste (tempel) langsung ke dalam editor tersebut.

Cara 2 (Import File): Klik menu Script di bagian atas editor, lalu pilih Import dan cari file berformat .lua yang ingin Anda gunakan di komputer Anda.

Langkah 3: Menjalankan dan Menyimpan Script
Setelah kode script masuk ke dalam editor, klik menu Script di sudut kiri atas jendela editor.

Pilih opsi Save & Run (Simpan dan Jalankan).   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

Periksa bagian Console di bagian bawah layar:   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

Jika script berhasil dimuat dan tidak ada kesalahan penulisan (error), biasanya akan muncul teks status atau pesan sambutan dari script tersebut.   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

Jika ada pesan error, periksa kembali kode script Anda (biasanya ada kesalahan ketik atau tanda baca).

💡 Tips Tambahan:
Pengujian: Coba jalankan fungsi script tersebut (misalnya dengan menahan klik kiri atau menekan tombol tertentu sesuai instruksi pembuat script) untuk memastikan script berfungsi dengan baik.   
Mouse macros for A4Tech Bloody, X7, Logitech and Razer mice!

G HUB Versi Lama: Jika Anda masih menggunakan software versi lama yaitu Logitech Gaming Software (LGS), caranya hampir serupa: buka pengaturan mouse 
→
→ pilih ikon profil scripting 
→
→ klik ikon lembar kerja baru 
→
→ paste kode Lua 
→
→ klik ikon Save & Run Script.
