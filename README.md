Nama 	: Saepurohman	
Nim	    : 2405105	
Jurusan : Informatika (4)

1)	Penjelasan Bug
    •	total = n tidak menjumlahkan nilai, hanya mengganti dengan nilai terakhir.
    •	kategori_nilai tidak dipanggil (tidak diberi parameter).
2)	Jenis Error
    Keduanya termasuk Logic Error (program berjalan tapi hasil salah).
3)	Solusi
    •	Ganti total = n menjadi total += n
    •	Panggil fungsi dengan benar: kategori_nilai(rata)
4)	Jawaban Analisis
    •	Rata-rata salah karena tidak dijumlahkan.
    •	Kategori tidak tampil karena fungsi tidak dipanggil.
    •	Program tidak error, hanya hasilnya salah.
