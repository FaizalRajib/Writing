#### Nama : Muh. Faizal Rajib
#### Learning Track : Front-End Develovment
#### Challeng Patner : Serrum Gudskul
#### Kelompok : FE 25
#### Week 3

#### **Day 1 JavaScript Intermediate.**
Array adalah variable yang mempunyai index sehingga dapa menyimpan sebuah data yang bertipe sama.

array adalah sebuah tipe data yang dapat menampung banyak data yang memiliki tipe data yang berbeda 

```
	// ================= Array ============================
	// mampu menyimpan banyak data, dan bisa menyimpan berbagai macam tipe data

	let arr = ["hello", 1, true]

	// cara akses aray 
	console.log(arr) //cara memanggil seluruh data array
	console.log(arr[0]) //cara memanggil index ke 0
	console.log(arr[1]) //cara memanggil index ke 1
	console.log(arr[2]) //cara memanggil index ke 2

```
propertie yang dimiliki oleh array "".lenght" untuk mengecek berapa banyak jumlah data pada array tersebut
```
    console.log((arr.length))

    let arrBuah = [
        "Jeruk", //index ke-0
        "Semangka", //index ke-1
        "Pepaya", //index ke-2
        "Rambutan" //index ke-3
]
```

array .push digunakan untuk menambhakan data baru ke dalam array
```
    arrBuah.push("duku")//menambah data baru ke array yang berposisi pada index paling akhir
```

menambah data ke index 0 atau data paling depan 
```
    arrBuah.unshift("Anggur")//menambah data baru ke Array yang berposisi pada index paling depan yang bernama Anggur
```

untuk menghapus data terakhir pada array
```
    arrBuah.pop()
```
untuk menghapus data paling pertama pada array
```
    arrBuah.shift()
```

.splice yang berguna untuk mengubah konten yang berada dalam array baik dengan menghapus atau menggantinya atau kita juga bisa menambahkan data baru.  untuk mengakses bagian didalam array tanpa memodifikasinya kita bisa menggunakan .slice
.splice atau slice
```
//Syntax .splice memiliki 3 parameter
    namaAray.splice(start)
    namaAray.splice(start, deleteCount)
    namaAray.splice(start, deleteCount, item1)
    namaAray.splice(start, deleteCount, item1, item2)
    deleteCount = berapa banyak data yang akan didelete
```

akan menghapus dimulai dari index ke 2 sampai akhir
```
    arrBuah.splice(2);
```

untuk menghapus index ke-2 saja
```
    arrBuah.splice(2, 1);
```
untuk menngganti index ke-2 dari semangka menjadi Buah Naga 
```
    arrBuah.splice(4,1,"Buah Naga"); 
```
untuk menambah data tanpa harus menghapus data
```
    arrBuah.splice(2,0,"Langsat"); 
```

Syntax slice memiliki 2 parameter
slice cuman mengembalikan shallow copy, kita ngambil sambil meng-copy tanpa mengubah struktur arraynya
```
    namaArray.slice()
    namaArray.slice(start)
    namaArray.slice(start, end)
```
```
    let slice = arrBuah.slice(2,4)
    console.log(slice);

    console.log(arrBuah);
```

untuk menambah data array ke dalam array
```
    arrBuah.push(["Pisang","Durian"]) 
```

untuk mengubah data array 
```
    let hewan = ["Kelinci","Kambing"]
    hewan[0] = "Kucing";
```


//================= Array Loop ===========================
console.log(arrBuah);

Menggunakan cara biasa kita bakalan capek untuk menampilkan data jika jumlahnya terlau banyk

proses looping untuk menampilkan data dari awal ke terakhir
```
    for (let i = 0; i < arrBuah.length; i++){
         console.log(arrBuah[i])
     }
```

untuk menampilkan data dari belakang ke depan
```
    for (let i = arrBuah.length-1; i >= 0; i--){
         console.log(arrBuah[i])
    }
```

for ... of ... dan forEach tidak dapat melakukan looping dari belakang

```
    for (let buah of arrBuah){
        console.log(buah)
    }
```

jika untuk sekedar menampilkan data (tanpa return)
```
    arrBuah.forEach((element, index) => {
        console.log(index, element)
    });
```

jika kita butuh datanya di return lagi maka kita butuh yang namanya mapping
bisa dengan return
kalau kita menggunakan map pasti dalam array dan total yang di return pun sama dengan total yang sedang dimappping
```
    // arrBuah.map((item, index) => {
    let buahSegar = arrBuah.map((item, index) => {
            if ( index % 2 == 0){
                return item + " " + "segar"
            }
        // console.log(item)
    })

    console.log(buahSegar)
```
kasus yang berbeda 
saya ingin merubah data dibawah menjadi persen 
```
    let angkaDes = [
        0.45,
        0.67,
        0.23,
        0.76
    ]

    let angkaPersen = angkaDes.map((item) =>{
        return item * 100 + "%"
    })

    console.log(angkaPersen)

    let angkaPersenForEach = []
    angkaDes.forEach((item) =>{
         angkaPersenForEach.push(item * 100 + "%")
    })

    console.log(angkaPersenForEach)
```
array multi dimensi
```
    let arrMulti = [
        ["nama","rajib"],
        ["umur", 21],
        ["kelas","js"]
    ]

    console.log(arrMulti[0][1])
    arrMulti[2][1] = "CSS"
    console.log(arrMulti[2][1])
```
#### **Day 2 Js Inermediate Objek.**

Dalam kehidupan nyata Objek adalah sesuatu yang bisa dilihat dan dirasakan

Objek didunia nyata dapat kita modelkan didalam programming
jadi pada programming Objek adalah sebuah tipe data pada varibale yang menyimpan properti dan fungsi (method)

Contoh objek mobil dengan properti nilai dan method
properti 
name = "fiat"
model = "500"
weight = "850kg"
color = "white"

method
start()
drive()
brake()
stop()

Akses Objek 
```
    let siswa = { 
        nama : 'Rajib',
        umur : 21,
        hobi : 'Rebahan',
        "nomor HP" : "081257325873" //penulisan variable objet menggunakan spasi pada nomor HP
    }

    // cara akses objek terbagi menjadi 2
    // 1. dot notation
    // ekspektasi outpu = rajib
    console.log(siswa.nama);

    // 2.bracket
    console.log(siswa['nama']);

    // cara mengakses nomor HP yang memilikli Spasi 
    console.log(siswa["nomor HP"]);

    // memanggil nama objek dengan variabel
    let properti = 'umur';
    console.log(siswa[properti]);
```

Array Of Object adalah sebuah array yang menyimpan banyak object sebagai nilainya, yang artinya indexnya itu adalah object
```
    let users = [
        {
            nama:"faizal",
            umur: 21,
            alamat:"makassar"
        },
        {
            nama:"kasman",
            umur: 19,
            alamat:"makassar"
        },
        {
            nama:"alfing",
            umur: 21,
            alamat:"jeneponto"
        },
    ];

    console.log(users);

    let data = users.map((el) => {
        console.log(el.nama);
        el.status = "Aktif"
    });
```

Assing membuat agar properti lama kita bisa di ganti
```
    let hewan ={
        nama: "kucing",
        kaki: 4,
        warna: "putih"
    };

    console.log(hewan);


    // nama_obj.properti_objek = value_baru
    hewan.nama = "Kambing"

    //nam_obj['properti_obj'] = value_baru
    hewan['warna'] = "hitam" 
    console.log(hewan)
```

create key Membuat atau menambah properti baru kedalam objek
```
    let buku = {
        judul: 'mantan jadi manten',
        penulis: 'hayati',
        "judul halaman" : 250
    }

    console.log(buku);

    // menambah propertie tahun terbit
    buku.tahun = 2022;
    buku.penerbit = 'global'

    console.log(buku);

    buku["edisi"] = 20;
    console.log(buku)
```

create objek
```
    // create obkjec 
    // note : key pada object biasanya disebut juga dengan properti

        let nama_obj = {
            key: "value",
            key: "value"
        };

        let siswa = { 
            nama : 'Rajib',
            umur : 21,
            hobi : 'Rebahan',
            "nomor HP" : "081257325873" //penulisan variable objet menggunakan spasi pada nomor HP
        }

        console.log(siswa['nama']);
```

delete
```
    let hewan ={
    nama: "kucing",
    kaki: 4,
    warna: "putih"
    };

    console.log(hewan);

    delete hewan.warna;
    console.log(hewan);

    hewan.jenis = "Mamalia"
    console.log(hewan)
```

loop
```
    let hewan ={
    nama: "kucing",
    kaki: 4,
    warna: "putih"
};

console.log(hewan);

delete hewan.warna;
console.log(hewan);

hewan.jenis = "Mamalia"
console.log(hewan)
```

method
```
    const greeting = {
    welcome: function(){
        return "Halo Selamat Datang";
    },
    afterPay: function(){
        return "Terima kasih sudah membeli produk kami";
    }
};

console.log(greeting.welcome());
console.log(greeting.afterPay());

let siswa = {
    nama: "kasman",
    umur: 20,
    hobi: "futsal",
};

console.log(siswa);

//membuat array dari object dimana keys adalah propertie dari objek
console.log(Object.keys(siswa)); 

//membaut array dari object mengambil dari value
console.log(Object.values(siswa));
```

Nested Objek
```
    // nested objek adalah menyimpan objek didalm objek
let buku ={
    judul: 'Duduk Dulu',
    penulis: 'Syahid Muhammad',
    tahun: 2021,
    penerbit:{
        Penerbit1:{
            Berdiri: 2019,
            Kota: "Makassar",
            Provinsi: "Sulawesi Selatan",
        },
        Penerbit2:{
            Berdiri: 2019,
            Kota: "Buton",
            Provinsi: "Sulawesi Tenggara",
        }
    }
}

console.log(buku.penerbit.Penerbit1.Kota);
```
#### **Day 3 JavaScript Module.** 

Modules adalah reusable code yang dapat di export dari suatu file javascript dan di import ke file javascript yang lain.

Reusable code adalah data yang dapat digunakan berulang kali.

dengan javascript module memungkinkan kita untuk memisahkan kode menjadi file yang berbeda sehinggah kita bisa memantaice codenya dengan mudah.

JS modules adalah cara untuk memisahkan kode ke file yang berbeda agar lebih mudah di kelolah dan kode tidak terlalu menumpuk didalam satu file

2 kata kunci spesial yaitu export dan import
export => dari dalam keluar
import => dari luar kedalam 

JavaScript - Recursive
Recursive ini termasuk kedalam paradigma pemrograman.

Recursive adalah sebuah algoritma dimana algoritamnya ini sebagai pengganti perulangan, Recursive dibuat menggunakan fuction yang memanggil diri dia sendiri. 

Kenapa sih dibutuhkan recursive ini?
Recursive ini digunakan untuk perhitungan matematika yang cukup rumit.

jepang.js
```
    //kita dapat melakukan export pada variable, function, kelas

    //kata kunci "export" dapat melakukan banyak export
    //kata kunci "export" ditangkap import
    //menggunakan kurung kurawal

    export let motor = [
        "Suzuki",
        "Yamaha",
        "Honda",
        "Kawasaki"
    ]

    //export default cuman bisa 1 yang di export
    //export default ditangkap tanpa kurung kurawal
    let entertaiment = ["anime","manga","wibu","drama"]
    export default entertaiment
```

script.js
```
    // function deretAngka{
    //     //base case
    //     // titik paling kecil (berhenti)

    //     //recursion case
    //     // titik dia memanggil diri dia sendiri 
    // }

    function deretAngka(n){
        if (n == 1){
            console.log(n);
        } else {
            deretAngka(n-1)
            console.log(n);
        }
    }
```

indonesia.js
```
    import entertaiment, { motor } from "./jepang";

    console.log(entertaiment);
    console.log(motor);
    deretAngka(2);
```




#### **Day 4 JavaScript Intermediate - Asynchronous.**

Asynchronous adalah sebuah pendekatan pemrograman yang tidak terikat pada input output(I/O) protocol. Yang menandakan bahwa pemrograman asychronous tidak melakukan pekerjaannya secara eksesi baris program satu persatu secara hirarki

Js merukapan bahasa yang singel-thread, non-bloking, asynchronous.
- Singel - Thread simpelnya itu 1 jalur proses.
- Multi - thread itu banyak jalur.

Js Asynchronous memiliki 3 kunci utama
1. Callback
2. promises
3. Async await


```
    //========== Callback ========
    // setTimeout(() =>{
        //     console.log("A");
    // }, 2000)


    // // butuh proses yang memakan waktu
    // //callback -> function yang dijadikan sebagai argumen

    // setTimeout(() => {
    //     console.log("B");
    // }, 1000)

    // console.log("C");

    // ============= Promise ================

    let nontonPromise = new Promise((resolve, reject) => {
        setTimeout(() => {
            resolve("nonton terpenuhi")
        }, 2000)
    })


    //eksekusi proses
    console.log("A");

    //cara tangkap promise
    nontonPromise.then(
        result => {
            console.log(result);
        }
    )

    console.log("C");
```

#### **Day 5 Web Storage.**
Web storage adalah salah satu Web API yang dapat menyimpan data secara lokal pada sisi client. Berbeda dengan objek atau array, data yang disimpan pada objek atau array JavaScript bersifat sementara, dan akan hilang jika terjadi reload atau pergantian URL pada browser. Sedangkan data yang disimpan pada Web Storage akan bertahan lebih lama karena data akan disimpan pada storage browser

Data yang disimpan web storage tersedia berdasarkan domain. Artinya, data pada suatu domain web hanya dapat diakses oleh domainnya itu sendiri. Web storage dapat menampung sebesar 10MB untuk satu domain
