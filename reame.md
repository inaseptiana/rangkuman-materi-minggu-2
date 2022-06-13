# materi minggu ke 2
-----------------
## 1.looping
Looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi berhenti tercapai.
 
 - for loop > merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan. for loop di gunakan saat kita tau berapa kali pengulangan yang harus di lakukan 

 didalam for loop terdapat tiga tahapan (start, stop, step)

contoh:
let angka = 1;
        for (angka; angka <= 10; angka++) {
            console.log(angka);
        }

- while loop > akan menjalankan instruksi pengulangan kondisi bernilai TRUE. while loop di gunakan saat kita tidak tau pasti berapa kali pengulangan.

- do while > Terkadang kita ingin setidaknya menjalankan pengulangan 1 kali sebelum dilakukan pengecekan kondisi. do while langkah awal adalah membuat dulu kondisi baru pengecekan

## 2. function
Function adalah sebuah blok kode dalam sebuah grup untuk menyelesaikan 1 task/1 fitur.
Saat kita membutuhkan fitur tersebut nantinya, kita bisa kembali menggunakannya.
contoh:
function greeting() {
    return 'Hello world';
};

greeting = adalah identitas dari function
parameter = adalah input dari sebuah fungsi
return = adalah hasil dari sebuah fungsi
argument = adalah nilai yang dimasukan ke dalam suatu fungsi

## 3. object
Objek JavaScript dapat menampung properti dan nilai sebanyak apapun dengan tipe data yang beragam.
contohnya:
let orang ={
    nama: 'sarah'
    umur: 23
    pekerjaan: 'programmer'};

keteranganya 
let orang = nama object
nama = nama properti
sarah = nilai

### cara mengakses nilai di dalam properti
- dot notation
console.log(nama object.nama properti)

-Bracket Notation
object['properti']

### menambah properti baru
- dot notation
let objek = { namaProperti1: nilaiProperti1 };

objek.namaProperti2 = nilaiProperti2;
- bracket notation
let objek = { namaProperti1: nilaiProperti1 };

objek['namaProperti2'] = nilaiProperti2;

console.log(objek);
### menghapus properti
delete namaobject.namaproperti
delete namaobject[namaproperti]

## 4. dom
DOM adalah singkatan dari Document Object Model.
Dengan adanya DOM ini, JavaScript diberi akses untuk membuat HTML menjadi dinamis, seperti:

- Mengubah element HTML pada halaman website.
- Mengubah attribute HTML pada halaman website.
- Mengubah CSS style pada halaman website.
- Menambah dan/atau menghapus element maupun attribute HTML.
- Menambah HTML event (contoh: efek klik pada mouse, hover pada mouse, dan lain-lain) pada halaman website.
Berinteraksi dengan semua HTML event di website.

Di HTML DOM, semua element HTML dari sebuah website dianggap sebagai objek. Dan sama seperti objek JavaScript pada umumnya, objek element HTML di HTML DOM juga mempunyai properti dan method atau yang lebih dikenal dengan istilah DOM Property dan DOM Method.

Jadi untuk mengubah nilai properti dari element HTML, kita bisa menggunakan DOM Property dan untuk memanggil fungsi dari suatu element HTML, kita bisa menggunakan DOM Method.



