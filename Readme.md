# dokumentasi
Isinya tentang Dokumentasi

--- Tahapan menggunakan Git ---

[ Pushing yang benar di Git / WSL ] : Ini flow yang benar ketika kamu ingin push project kamu ke Github.

// Git checkout -b "feature/namabranchbaru" : untuk membuat branch baru
// Git add .                                : untuk menambahkan code kamu ke staging
// Git commit -m "commit message"           : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository

[ Setelah kamu berhasil commit seperti contoh diatas, kamu bisa mengambil data terbaru dari development untuk ditempatkan dibawah alur project kamu,
jadi walaupun kamu akan menggabungkan dengan commit terbaru dari development.]

[ Kamu harus "pulling" dari development terlebih dulu dan melakukan rebase, agar project kamu tidak terjadi conflict dan tetap mendapat update terbaru dari commit sebelumnya.] 

// Git checkout development
// Git pull                                 : untuk menarik update terbaru dari project yang sudah kamu buat
// Git chekout "feature/namabranchbaru"
// Git rebase development                   : untuk mengambil semua data terbaru yang telah kamu pull untuk menempatkannya di bawah commit yang telah kamu buat.
// Git status                               : cek status sebelum pull
// Git push                                   


--- Ganti Remote di Git ---

[ Mengganti remote yang ada di Git / WSL ] : Fungsinya agar kamu tidak mengganti source code / sumber asli code dengan code terbaru yang akan kamu push.
jadi pastikan kamu ganti remotenya setelah kamu clone repository seseorang.

// Git remote -vv : untuk cek keseluruhan remote kamu dengan mendetail.
// Git remote add <nama remote> <url remote> : untuk menambahkan remote di wsl kamu.
// Git remote remove <nama remote> <url remote> : untuk menghapus remote di wsl kamu.
  
  
