#### Nama : Muh. Faizal Rajib
#### Learning Track : Front-End Develovment
#### Challeng Patner : Serrum Gudskul
#### Kelompok : FE 25
#### Week 5
#### 24 - 28 Oktober 2022

#### **Day 1**

react dikembangkan oleh tim facebook

react adalah adalah frameworok view library javascript untuk membuat tampilan (UI) pada website.

Alternative
- Angular
- Vue
- Svelte

React JS membuat aplikasi front-end menjadi lebih cepat walaupun harus menghandle beberapa data

react berinteraksi dengan dom menggunakan virtual dom

#### **Day 2**
State adalah sebuah properti atau variabel yang didefinisikan di dalam sebuah class, sedangkan props adalah properti atau variabel yang berasal dari luar class atau class parent. Untuk membuat State menggunakan method getInitialState, sedangkan untuk membuat props menggunakan atribut dalam tag (XML).

Perbedaan yang mendasar dari keduanya adalah pada props kita tidak dapat mengubah nilainya secara langsung, sedangkan pada state kita dapat melakukan hal tersebut. State bersifat privat atau tidak dapat digunakan di komponen lain, sedangkan props dapat digunakan di komponen lain (komponen child).

#### **Day 3**
props dan stater adalah data

state adalah data yang tinggal didalam komponen tersebut

props adalah data yang dikasih atau pemberian data

Component itu bagian bagian didalam website

kalau ada data yang ingin ditampilkan dan kemungkinan datanya itu dapt berubah kita tidak bisa menggunakan variable biasa, tapi menggunakan state

#### **Day 4**
lifecycle simpel nya itu siklus hidup
dibagi menjdi 3 
1. Mounting - memunculkan / komponen baru muncul
2. Update - memperbahrui
3. Unmounting - component nya itu menghilang

life cycle memiliki side effect. contoh ketika component pertama kali muncul maka akan langsung menampilkan data dari API

pada tiap life cycle, kita dapat menambahkan egek yang diperlukan, contoh 
- ketika komponen muncul, ambil data pakai fetch
- ketika data state berubah, lakukan filter
- ketika komponen  hilang, kata state jangan di update

#### **Day 5**
Component adalah salah satu core dari react js, component membagi UI dalam satuan - satuan kecil. artinya dalam 1 page ada beberapa component yang bisa kita buat