#### Nama : Muh. Faizal Rajib
#### Learning Track : Front-End Develovment
#### Challeng Patner : Serrum Gudskul
#### Kelompok : FE 25
#### Week 2
.

#### **Day 1 Looping**
Looping Looping adalah sebuah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi berhenti/stop tercapai.

Perulangan For Loop
**For Loop** Merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan. for loop memiliki aturan tersendiri dalam penulisannya.
contohnya: 
```
	for (let i = 1; i <= 10 ; i++){
    	if (i == 6) {
        	console.log(i, "Yes Ketemu")
    	} else {
        	console.log(i); 
    	}
	}
```

Perulangan While 
**Perulang While** merupakan perulangan yang bersifat indefinite alias tidak pasti, atau bahkan tidak terbatas.
Contohnya : 
```
	let i = 1;
	let isKetemu = false

	while(!isKetemu){
    	if(
        	i % 2 == 0 &&
        	i % 3 == 0 &&
        	i % 4 == 0 &&
        	i % 5 == 0 &&
        	i % 6 == 0
    	){
        	console.log(i);
        	isKetemu = true
    	}
    	i++
	}
```

Perulangan Do While 
**Perulangan Do While** melakukan perulangan dulu, kemudian memeriksa kondisinya atau sayaratnya.
Contohnya :
```
	do{
    	if(
        	i % 2 == 0 &&
        	i % 3 == 0 &&
        	i % 4 == 0 &&
        	i % 5 == 0 &&
        	i % 6 == 0
    	){
        	console.log(i);
        	isKetemu = true
    	}
    	i++
	} while (!isKetemu)
```

**Function**
Function adalah kode program yang dirancang untuk menyelesaikan sebuah tugas tertentu, dan merupakan bagian dari program utama. Ketika di sadur ke dalam bahasa indonesia, function ini di sebut juga sebagai fungsi. Ada beberapa penulisan function :
1. function classic
```
	function myFuction (parameter) {
		//Perintah yang dijalankan
	} 
```

2. Arrow function
```
	let myFunction = () => {
		//kode yang dijalankan
	}
```

3. function variable
```
	let myFuction = function (){
		//kode yang akan dijalankan
	}
```

#### **Day 2 Type Data**
Ada beberapa type data
**Primitive**
1. String
2. Number
3. Bolean

**Non-Primitive**
1. Array
2. Method


**String**
Nilai dari type data ini selalu dibungkus dengan tanda kutip 2 ("Nilai dari string"), jadi segala sesuatu yang bungkus oleh tanda kutip 2 ini akan di baca String walaupun itu angka.
Penulisan String :
```
	let hewan = "Kancil";

	console.log("Ini adalah " + hewan);
	console.log(`Ini adalah ${hewan}`);
```

#### **Day 3 DOM**
DOM (Document Object Model) adalah dokumen (HTML) yang dimodelkan dalam sebuah objek.
DOM adalah jembatan supaya bahasa pemrograman dapat berinteraksi dengan dokumen HTML, dengan DOM, JS dapat memanipulasi HTML.
DOM bukan merupakan bahasa JavaScript. Tapi merupakan web API untuk membuat website cara akses nya menggunakan JavaScript. DOM tidak bisa digunakan pada Server.
**Traversing**
Kebawah: 
1. getElementById
2. getElementsByClassName
3. getElementsByTagName
4. querySelectoriFamily
5. childern

Keatas:
1. parentElement
2. closest()

kesamping
1. nextElementSibling
2. previousElementSibling

HTML Collection

#### **Day 4 DOM Manipulation**
DOM Manipulation berinteraksi dengan DOM API untuk mengubah/memodifikasi dokumen HTML yang akan dirender di browser web.
contoh index.html :
```
    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
            <style>
            #tess{
                width: 100px;
                height: 20px;
                background-color: brown;
            }
    </style>    
        </head>
        <body>
            <div id="tess"></div>
            <div id="app"></div>
            <div id="end">
                <a href="google.com" class="link">Google</a>
            </div>

            <script src="script.js"></script>
        </body>
    </html>
```
Contoh scrip.js: 
```
    let app = document.getElementById("app")

    console.log(app)

    //tag htmlnya akan di baca sebagai perintah
    app.innerHTML = "<h1>Hallo</h1>"  

    //walaupun itu element html akan tetap dibaca text
    // app.innerText = "<h1>Apa Kabar</h1>" 

    let p = document.createElement("p")
    p.innerText = "Ini adalah paragraf";

    app.append(p)
    // console.log(p);

    let p2 = document.createElement("p")
    p2.innerText = "paragraf ke-2"
    app.appendChild(p2)

    //appendChild tidak bisa input data string
    app.append("menggunakan append")
    // app.appendChild("appendChild")

    let end = document.getElementById("end")
    //end.remove

    let link = document.getElementsByClassName("link")[0]

    console.log(link.attributes)
    console.log(link.getAttribute("href"));
    link.setAttribute("id","google")

    link.style.color ="black"
    link.style.border = "1px solid black"
    link.style.padding = "5px 20px"
    link.style.backgroundColor = "aqua"

    let tess = document.getElementById("tess")

    let tessStyle = getComputedStyle(tess)
    console.log(tessStyle.height)
```

#### **Day 5 DOM Event**
file index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script src="script.js"></script>
</head>
<body>
    //cara 1 memberikan event
    <h1 onclick="alert('selamat datang')">Hallo</h1>

    <p id="paragraf">click me</p>

    <button id="btn">klik saya</button>
</body>
</html>
```
**file script.js**
```
let paragraf = document.getElementById("paragraf")

//cara ke - 2
paragraf.onclick = function (){
    alert("ini dari paragraf ")
}

// paragraf.onclick = tampilkanAlert

paragraf.onclick = function(){
    confirm("apakah ini dari paragraf?")
}

function tampilkanAlert(){
    alert("ini alert")
}

//cara ke 3
let button = document.getElementById("btn")
button.addEventListener("click", function(event){
    console.log(event.target)
    alert("ini dari button")
})
// // button.addEventListener("click", tampilkanAlert)

// button.addEventListener("click", function(){
//     confirm("apakah dari button?")
// })
```

**file  counter.html**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script src="counter.js"></script>
</head>
<body>
    <div>
        <button id="decrement">-</button>
        <span id="counter">0</span>
        <button id="increment">+</button>    
    </div>
</body>
</html>
```

**file counter.js**
```
let btnDecrement = document.getElementById("decrement")
let btnIncrement = document.getElementById("increment")
let counter = document.getElementById("counter")

let angka = 0

btnIncrement.addEventListener("click", function(){
    angka = angka + 1
    counter.innerText = angka
    // console.log(angka)
    // console.log("increment")
})

btnDecrement.addEventListener("click",function(){
    // console.log("decrement");
    angka--
    counter.innerText = angka
})
```

**file login.html**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script src="login.js"></script>
</head>
<body>
    <dicv class="container">
        <form id="sign-in">
            <h1>Sign In</h1>

            <div class="field">
                <label for="username">Username</label>
                <input type="text" id="username" name="username" / >
            </div>

            <div class="field">
                <label for="password">Password</label>
                <input type="text" id="password" name="password" />
            </div>

            <button type="submmit">Login</button>
        </form>
    </dicv>
</body>
</html>
```

**file login.js**
```
let loginForm = document.querySelector("#sign-in")
let inputUsername = document.querySelector('#username')
let inputPassword = document.querySelector('#password')

let user = {
    username:"Rajib",
    password:"123"
}

loginForm.addEventListener("submit", (event) => {
    event.preventDefault()
    console.log(inputUsername.value)
    console.log(inputPassword.value)

    let userLogin = {
        username: inputUsername.value,
        password: inputPassword.value
    }

    console.log(userLogin);

    let login = userLogin.username == user.username && userLogin.password == user.password;


    if(userLogin.username == user.username && userLogin.password == user.password){
        console.log("selamat anda berhasil login")
    } else {
        console.log("username dan password salah"); 
    }
    //membersihkan form
    //cara 1
    loginForm.reset()

    // cara2
    // inputUsername.value =""
    // inputPassword.value = ""

    //console.log("ini dari form yg di submit");
})
```