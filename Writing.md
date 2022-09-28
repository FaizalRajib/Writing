### Nama               : Muh. Faizal Rajib
### Learning Track     : Front-End Web Develoment 
### Challeng Patner    : Serrum Gudskul
### Kelompok           : FE 25

#### Hari Senin 19 September 2022.Git dan GitHub.
Jadi kami malakukan proses pengintalan Git.
"Command Line" atau "Command Line Interface" sebenarnya yang dimaksud adalah shell yang berbasis teks. Shell adalah program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi. 
##### Contoh CLI :
 - sh
 - bash (di linux)
 - zsh
 - cmd.exe (di windows)

Jadi ada beberapa perintah dasar CLI.
1. "pwd" (Print Working Direktori) untuk menampilkan posisi kita berad.
2. "ls" (List) untuk menampilkan isi file direktori
3. "cd (direktori)" atau change direktori untuk pindah direktori
4. "cd .." untuk keluar folder
5. untuk menampilkan file yang disembunyikan atau hidden tinggal tambahkan -a contoh "ls -a"
6. "mkdir" untuk membuat folder baru
7. "touch" untuk membuat file 
8. "nano" untuk menedit isi file

#### GIT dan GITHUB
Git adalah software sedangkan Github adalah tempat mengupload kodingan
git adalah alat untuk membantu kita membuat sebuah version system, version control di software yang kita buat. simpelnya kita membuat checkpoint. kita bisa kembali ke data sebelumnya, kita bisa ke sesudahnya, kita bisa berpindah pindah data.
file - file yang disimpan menggunakan git kita dapat melacak perubahan dan sebagai sarana kolaborasi juga

##### Setelah menginstal git lakukan setup awal
```markdown
git config --global user.name "FaizalRajib"
git config --global user.email "muhfaizalrajib@gmail.com"
```

##### Cek Apakah Sudah Berhasil
```markdown
git config --list
```

##### Kemudian tempelin git init atau memasang git kedalam projek kita dan dapat melacak perubahan
```markdown
git init
```
##### Kemudian lacak perumbahan
```markdown
git status
```

##### Untuk melacak perubahan file 
```markdown
git add . 
```

##### Memberikan keterangan jika ada perubahan
```markdown
git commit -m "message" 
```

#### Hari Selasa 20 September 2022. HTML
HTML adalah singkatan dari Hypertext Markup Language. digunakan utnuk menampilkan konten pada browser.

##### Struktur dasar HTML
```html
<html>
	<head>
    	<title>Document</title>
	</head>
	<body>
	Isi Konten
	</body>
</html>
```

#### Untuk memasukkan gambar 
```
	<img src="http://www.w3.org/2000/svg" alt="" srcset="">
```

**Penjelasan**
src="" berfungsi untuk mengarahkan ke lokasi gambar berada agar dapat di tampilkan. Bisa menggunakan link seperti contoh  diatas dan bisa juga menggunakan lokasi folder gambar berada.

#### Untuk membuat link menggunakan ancor
```
	<a href="#">Instagram</a>
```

**Penjelasan**
href="#" berfungsi untuk mengarahkan link dari Instagram. jadi tanda # itu bisa di ganti menjadi link instagram yang ditujukan.

#### Hari Rabu 21 September 2022. CSS (Cascading Style Sheets)
Ada 3 komponen dasar dari penulisannya
```
	.elementHTML {
		property : value
	}
```

Ada 3 cara untuk melakukan styling
##### Inline
```
	<h1 style="background-color: aqua;">Hi.. I'm Rajib</h1>
```
**Penjelasan**
Kita langsung menuliskan stylenya langsung pada element HTML nya

##### Internal
```	
    <style>
        h1 {
            border: black 1px solid;
        }
    </style>

```
**Penjelasan**
Kita menuliskan tag style didalam tag head, kemudian didalam tag style ini kita masukkan element HTML yang ingin kita styling.

##### Eksternal
Kita butuh  file tambahan yaitu style.css dan membutuhkan penghubung antara dile HTML dan file CSS. Pada file HTML perintah untuk menghubungkan HTML dan CSS berada didalam tag <head>
```
<link rel="stylesheet" href="style.css">
```
**Penjelasan**
Jadi perintah diatas memberitahukan bahwa file HTML nya akan terhubung ke sebuah file CSS yang bernama style.css
#### Hari Kamis 22 September 2022. Algoritma dan Introduction JavaScript
- Algoritma adalah langkah - langkah untuk menyelesaikam suatu masalah secara logis yang tersusun secara sistematis 

Contoh Masalah = Saya haus?

Langkah - langkah nya
1. Pergi ke dapur
2. Ambil gelas di rak
3. Pergi ke dispenser
4. Isi gelas dengan air
5. Air Siap di minum

Proses tersebut dilakukan dengan cara yang logis (masuk akal) dan sistematis (terurut).
**Ciri - cir algoritma** 
- Input Memiliki 0 atau lebih inputan Contoh Kopi saset
- Output Memiliki minimal 1 buah output Segelas Kopi hangat
- Definiteness (Pasti) Instruksi jelas tidak ambigu contoh mulai dari menyiapkan kopi sampai ke tahap pembuatannya
- Finiteness (ada batas) memiliki titik berhenti contoh kopi selesai dibuat
- Effectiveness Sebisa mungkin tepat sasaran dan efisien

**Jenis Proses Algoritma**
- Sequence 
- Selection
- Iteration
- Concurrent

**Penyajian Algoritma**
- Deskriptif
- Flowchart
- Pseudo Code

**JavaScript** adalah bahasa pemrograman yang sangat powerful yang digunakan untuk logic pada sebuah website dan juga dapat membuat website menjadi intraktif dan dinamis.
Tipe data pada JavaScript 
- String
- Number
- Boolean
- Object
- Array

#### Hari Jum'at 23 September 2022. Js Dasar Condicional dan Looping
Condicional Statmen akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan perintah tersebut. yang dicek apakah kondisi tersebut TRUE(benar) jika TRUE maka code didalam kondisi tersebut dijalankan.

**Contoh kasus:**
Jika Cuaca Cerah hari ini, maka kita akan pergi keluar
Jika Alarm berbunyi, maka kita akan bangun dari tidur
Jika Lelah, maka kita akan istirahat
Jika Lapar, kita akan makan

**Penulisan IF**
```
	if(kondisi){
		kode jika kondisi terpenuhi
	}
```

**Penulisan If Else**
```
	if(kondisi){
		kode jika kondisi terpenuhi
	} else {
		kode jika kondisi tidka terpenuhi
	}
```

**Penulisan If Else If**
```
	if(kondisi_1){
		kode jika kondisi_1  terpenuhi
	} else if (kondisi2) {
		kode jika kondisi_2  terpenuhi
	} else {
		kode jika kondisi tidka terpenuhi
	}
```

Percabangan ini bisa di kombinasikan dengan operator logika
contoh operator AND:
```
	if (nilai_x === 2 && nilai_y === 1){
		kode jika kondisi 1 dan 2  terpenuhi
	} else {
		kode jika kondisi tidak terpenuhi
	}
```

contoh operator OR:
```
	if (nilai_x === 2 || nilai_y === 1){
		kode jika kondisi 1 dan 2  terpenuhi
	} else {
		kode jika kondisi tidak terpenuhi
	}
```

selain operator logika bisa juga dikombinasikan dengan operator perbandingan
Contoh
contoh operator AND:
```
	if (nilai <= 80){
		kode jika kondisi 1 dan 2  terpenuhi
	} else {
		kode jika kondisi tidak terpenuhi
	}
```

Selain percabangan if, if else, dan if else if ada juga yang switch case
```
	switch(kondisi){
	case statement_1;
		kode jika kondisi_1 terpenuhi;
		break;
	case statement_2;
		kode jika kondisi_2 terpenuhi;
		break;
	case statement_3;
		kode jika kondisi_3 terpenuhi;
		break;
	default
		kode jika kondisi tidak terpenuhi
	}
```

Setelah Js Conditional, Selanjutnya Js Looping
Looping adalah sebuah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi berhenti/stop tercapai.

**For Loop**
Merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan.
for loop memiliki aturan tersendiri dalam penulisannya
```
    for(initialization; condition; post-expression){
        
    }
```

contoh penggunaan for loop 
```
    let angka = 1;
    for (angka; angka <= 10; angka++){
        console.log(angka);
    }
    //outputnya : 1 2 3 4 5 6 7 8 9 10
```