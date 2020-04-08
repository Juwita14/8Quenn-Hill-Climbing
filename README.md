# 8Quenn-Hill-Climbing
Inisial board awal dilakukan dengan random sehingga akan selalu acak. Kemudian fungsi Hill Climbing dipanggil untuk menyelesaikan permasalahan 8 Queen ini.
<br/>Hill Climbing adalah algoritma pencarian lokal. Ini adalah algoritma iteratif yang dimulai dengan solusi sewenang-wenang untuk suatu masalah, kemudian berusaha mencari solusi yang lebih baik dengan secara bertahap mengubah satu elemen dari solusi. Jika perubahan menghasilkan solusi yang lebih baik, perubahan tambahan dibuat untuk solusi baru, diulang sampai tidak ada perbaikan lebih lanjut yang dapat ditemukan. Algoritma tidak memelihara pohon pencarian, sehingga struktur data untuk simpul saat ini hanya perlu mencatat keadaan dan nilai fungsi tujuan. Algoritme pendakian bukit sering gagal menemukan tujuan ketika ada karena mereka dapat terjebak pada maxima lokal. 
Posisi letak ratu ditempatkan direpresentasikan sebagai '1' dan posisi lain ditampilkan sebagai '0'.<br/>
<br/>1.Utama (): Ini menerima input dari pengguna dan memeriksa apakah input tersebut valid, kemudian menghasilkan papan awal secara acak dan kemudian melakukan pendakian bukit. Akhirnya cetak jumlah langkah naik dan jumlah total restart acak yang digunakan.
<br/>2.printBoard(int (&board)[N]): untuk mencetak board saat ini.
<br/>3.copyBoard(int (&board1)[N], int (&board2)[N]): meng-copy board ke board lainnya
<br/>4.int calcEvaluationFunction(int (&board)[N]): untuk menghitung maximal local
