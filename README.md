# UTS Algoritma 1
=======================================================================================================================
UJIAN TENGAH SEMESTER
Program Studi : TEKNIK INFORMATIKA		Kelas		: TI.18.C2
Nama		: FAUZI AKBAR			Dosen		: AGUNG NUGROHO
Nim		: 311810855				Waktu		:130 Menit
Semester	: 1					Mata Kuliah	:Algortima &Pemograman
=====================================================================================================================

1.	Soal 1.a langkah pertama akan membaca inputan dari variable A dan B, yang akan di proses dimana X=A dan Y=B.
Jika di inputkan misal nila A=2 dan nilai B=4
Maka masuk  pada seleksi kondisi pertama yaitu perbandingan dimana X!=Y jika nilainya SALAH maka akan tercetak nilai X.
Jika nilai Benar maka akan dilakukan seleksi kondisi kedua yaitu X<Y nilai mana yang terpenuhi  BENAR atau SALAH maka nilai antara X atau Y ditambah nilai A atau B.
Dilihat dari inputan di atas dimana A=2 dan B=4 maka perbandinganya 2<4 bernilai benar sehingga nilai X akan ditambah dengan nilai A sampai kondisi pertama terpenuhi
	X!=Y					2!=4
	X=A					X=2
X=X+A				X=X+2
					X=2+2
					X=4
Jadi nilai X = 4 sehingga X!=Y terpenuhi menjadi 4!=4 bernilai SALAH dan tercetak nilai X=4

2.	Soal 1.b langkah pertama akan membaca inputan dari variable A dan B, yang akan di proses dimana X=A dan Y=B.
Jika di inputkan misal nila A=4 dan nilai B=7
Maka masuk  pada seleksi kondisi pertama yaitu perbandingan dimana X!=Y jika nilainya SALAH maka akan tercetak nilai X.
Jika nilai Benar maka akan dilakukan seleksi kondisi kedua yaitu X<Y nilai mana yang terpenuhi  BENAR atau SALAH maka nilai antara X atau Y ditambah nilai A atau B.
Dilihat dari inputan di atas dimana A=4 dan B=7 maka perbandinganya 4<7 bernilai benar sehingga nilai X akan ditambah dengan nilai A sampai kondisi pertama terpenuhi
	X!=Y					4!=7
	X=A					X=4
X=X+A				X=X+4
					X=4+4
					X=8
Karena nilai X sudah 8 maka kondisi kedua tidak terpenuhi 8<7 sehingga akan mengerjakan yang Y
	X!=Y					8!=7
	Y=B					Y=7
Y=Y+A				Y=Y+7
					Y=7+7
					Y=14
Karena nilai Y sudah 14 maka kondisi kedua tidak terpenuhi 8<14 sehingga akan mengerjakan yang X
	X!=Y					8!=14
	X=A					X=8
X=X+A				X=8+4
					X=12+4
					X=16
Karena nilai X sudah 16 maka kondisi kedua tidak terpenuhi 16<14 sehingga akan mengerjakan yang Y
	X!=Y					16!=14
	Y=B					Y=7
Y=Y+A				Y=Y+7
					Y=14+7
					Y=21
Karena nilai Y sudah 21 maka kondisi kedua tidak terpenuhi 16<21 sehingga akan mengerjakan yang X
	X!=Y					16!=21
	X=A					X=4
X=X+A				X=8+4
					X=12+4
					X=16+4
					X=20
Karena nilai X =20 maka kondisi ini masih terpenuhi 20<21 sehingga akan mengerjakan yang X
	X!=Y					20!=21
	X=A					X=4
X=X+A				X=8+4
					X=12+4
					X=16+4
					X=20+4
					X=24
Karena nilai X sudah 24 maka kondisi kedua tidak terpenuhi 24<21 sehingga akan mengerjakan yang Y
	X!=Y					16!=14
	Y=B					Y=7
Y=Y+A				Y=Y+7
					Y=14+7
					Y=21+7
					Y=28

Karena nilai Y sudah 28 maka kondisi kedua tidak terpenuhi 24<28 sehingga akan mengerjakan yang X
	X!=Y					16!=21
	X=A					X=4
X=X+A				X=8+4
					X=12+4
					X=16+4
					X=20+4
					X=24+4
					X=28

Jadi nilai X = 28 dan Y=28 sehingga X!=Y terpenuhi menjadi 28!=28 bernilai SALAH dan tercetak nilai X=28
 

3.	Soal nomor 2 
Pada soal ini inputan N akan di isi dengan 2 digit terakhir NIM masing masing mahasiswa. NIM saya 311810855 jadi nilai N akan di inputkan angka 55.
Berikut kode lengkapnya.
	Int N,X,T,Batas;
	N = 55 ;
	Batas = N + 100;
	X = 20;
	T = N;
	While ( T<=Batas)
		{
		T = T + X;
		X = X + 10;
		}
	Cout<< T.
Ketika nilai N di inputkan 55, dan nilai batas menjadi 155, sehingga nilai T menjadi 55 karena sama dengan nilai N. Dilihat dari  perintah while akan terjadi perulangan nilai T sampai kurang dari sama dengan nilai Batas.
Pada looping pertama
N = 55
Hasilnya :
T = T + X   				T = 55 + 20	= 75
X = X + 10				X = 20 + 10	= 30
Pada looping kedua
T = T + X   				T = 75 + 30	= 105
X = X + 10				X = 30 + 10	= 40
Pada looping ketiga
T = T + X   				T = 105 + 40	= 145
X = X + 10				X = 40 + 10	= 50
Pada looping ke empat
T = T + X   				T = 145 + 50	= 195
X = X + 10				X = 50 + 10	= 60

Hasil T = 195 Karena saat masuk ke looping selanjutnya nilai T sudah 195 <= 155 dan bernilai FALSE sehingga looping terhenti dinilai 195
