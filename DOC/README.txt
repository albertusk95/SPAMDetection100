Beberapa aturan teknis:
-----------------------

1. File dataset terletak di folder 'data' dalam folder 'NetBeansGen' dan bernama "dataset.arff" [DEFAULT]
	- Format ekstensi dataset untuk aplikasi ini sudah ditentukan, yaitu ARFF [FIX]
2. File penyimpan model terletak di folder 'data' dalam folder 'NetBeansGen' dan bernama "modelresult.dat" [DEFAULT]
	- Format ekstensi penyimpan model untuk aplikasi ini sudah ditentukan, yaitu DAT [FIX]
	- File penyimpan model ini harus dibuat dulu sebelum melakukan pembentukan model [FIX]
3. File teks input berada di folder 'data' dalam folder 'NetBeansGen' dan bernama "fileinput.txt" [DEFAULT]
	- Format ekstensi file input untuk aplikasi ini sudah ditentukan, yaitu TXT [FIX]
	- Aplikasi ini TIDAK menerima jenis karakter asing seperti kode untuk SMILEY, ICON, DLL yg sejenis [FIX]
	- Jumlah teks input yang akan diprediksi adalah 1 (SATU) buah [FIX]
4. Karakter yang diperbolehkan adalah [0..9][~`!@#$%^&*()-_+={[}]\|:;"'<,>.?/][a..z][A..Z] [FIX]
5. File EXE berada pada foldr dist dan bernama SPAMAssasin100.jar [FIX]
6. Cara menjalankan file JAR (tanpa lewat CMDLine)
	- Klik kanan pada file SPAMAssasin100.jar 
	- Pilih Open With
	- Pilih Java(TM) SE Platform Binary atau aplikasi sejenis untuk menjalankan java apps
7. Cara menjalankan file JAR (lewat CMDLine)
	- Masuk ke direktori tempat file JAR tersimpan
	- Ketikkan: java -jar SPAMAssasin100.jar
8. File JAR Weka (sebagai External Libraries) berada pada direktori dist/lib/ 
9. Di halaman SPAMDetection (utk prediksi), jika Anda mengklik tombol Exit dan memilih No, 
	besar kemungkinan layout dari UI akan berantakan. [50:50]
	