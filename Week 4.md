#### Nama : Muh. Faizal Rajib
#### Learning Track : Front-End Develovment
#### Challeng Patner : Serrum Gudskul
#### Kelompok : FE 25
#### Week 4

#### **Day 1 JavaScript Intermediate - Asynchronous - Fetch dan Async Await**
```
let nonton = (kondisi) => {
    return new Promise((resolve, reject)=>{
        if (kondisi == "jalan") {
            resolve("Nonton Terpenuhi")
        }
            reject("Batal Nonton")
    })
}

// untuk menjalankan kode promise diatas
// ada 2 cara
// - promise (then catch)
// - async await

// =====================
//promise
//namaPromise.then().catch()
// nonton("jana").then(result => {
//     console.log(result);
// }).catch(err => {
//     console.log(err);
// })

//async await
//buat async await function
// async function asyncNonton(){
//     try {
//         let result = await nonton("jalan")
//         console.log(result);
//     } catch (error) {
//         console.log(error);
//     }
// }

//async await
//let asyncNonton = async () => {}

// ======= FETCH ==============
// fetch -> obj promis
// - then catch
// - async await

//siapin data satu persatu
//let digimon = ["Agumon","Gabumon","Patamon"]

//API, data sudah tersedia
//https://digimon-api.vercel.app/api/digimon

// fetch("https://digimon-api.vercel.app/api/digimon").then(result => {    
//     console.log(result);
//     return result.json()
// })
// .then(result => {
//     console.log(result);
// })
// .catch(err => {
//     console.log(err);
// })

// short syntax
// fetch("https://digimon-api.vercel.app/api/digimon")
// .then(result => result.json ())
// .tehn(result=>{
//     console.log();
// })

// async await
let containerDigimon  = document.getElementById("list-digimon")
let digimons= []
let getDataDigimon = async () => {
    let response = await fetch("https://digimon-api.vercel.app/api/digimon")
    let digimons = await response.json()
    // console.log(result);
    // digimons = [...result]

    digimons.forEach(item =>{ 
        console.log(item)
        containerDigimon.innerHTML += 
        `<div>
            <img src="${item.img}" alt="" width="200px"
            <h3>${item.name}</h3>
        </div>`
    })
}

getDataDigimon();


// let digimon = ["Agumon","Gabumon","Patamon"]
// let containerDigimon  = document.getElementById("list-digimon")

// digimons.forEach(item => {
//     console.log(item);
    // containerDigimon.innerHTML += `<h3>${item}</h3>`
    
    // let txtDigimon = document.createElement("h3")
    // txtDigimon.innerText = item

    // containerDigimon.append(txtDigimon)
// })
```
#### **Day 2 Git dan Github lanjutan**
**Langkah Langkah Kolabaorasi**
1. masing - masing anggota lakukan git clone pada repo yang dibuat
2. Bagi tugas pada masing - masing anggota kelompok
3. pindah ke branch dev git switch dev
4. sebelum ngoding, lakukan git pull pada branch dev untuk update kode terbaru
5. Anggota membuat branch dari git branch [nama-branch]
6. Pindah ke dalan branch yang sudah dibuat git switch [nama - branch]
7. lakukan pengerjaan di dlm branch tersebut
8. jika fitur sudah selesai, sebelum di push lakukan langkah no 3, 4, dan 6
9. Lalu git merge dev untuk menhindari conflict di github
10. Jika ada conflict, bereskan semuanya
11. jika sudah aman, commit lalu git push origin [nama-branch]
12. lakukan pull request untuk merge ke branch dev
13. tunggu pull request di acc oleh team lead
14. Jika sudah, ulangi proses dari no 2

Note: langkah no 8 dan 9 dapat di ganti dgn git pull origin dev

#### **Day 3 Responsive Web Dsign dan Bootstrap 5**
Responsive Web Desing adalah langkah agar website yang kita buat dapat menyesuaikan dengan perangkat yang digunakan oleh user

cara mengguankan responsive
1. meta viewport
2. max-width
3. relativ unit
4. media query membutuhkan kata kunci @media
5, flex
6. grid

**Framework CSS**
1. Boostrap
2. Material UI
3.  Tailwind
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <div>
            <h1>Rajib</h1>
        </div>
        <div class="toggle-menu">
            
        </div>
        <ul class="Menu">
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <img src="https://img.freepik.com/free-vector/nature-scene-with-river-hills-forest-mountain-landscape-flat-cartoon-style-illustration_1150-37326.jpg?w=2000" alt="">
        <p class="rem">Halo ini dari rem</p>
    </div>
    
    <div class="container">
        <p class="em">Halo ini dari em</p>
    </div>

</body>
</html>
```
**style.css**
```
*{
    font-style: none;
    list-style: none;
}
nav{
    display: flex;
    justify-content: space-between;
}

.menu{
    display: flex;
    justify-content: space-around;
}

.menu li{
    margin: 0 2rem;
}

.container {
    font-size: 20px;
    width: 500px;
    /* height: 500px; */
    /* background-color: black;
    z-index: 100; */
}


/* font size dari root 16px */
.container .rem {
    font-size: 2rem;
}

.container .em {
    font-size: 2em;
}

img{
    /* width: 100%; */
    width: 100vw;
}

@media (max-width: 500px ) {

    .Menu{
        display: none;
    }

    .toggle-menu{
        background-image: url("menu-regular-24.png");
    }
}
```