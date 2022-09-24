# Writing-Minggu-ke-1
## **Unix Command Line Interface**

- **Command line interface** merupakan shell berbasis teks yang digunakan untuk menjalankan program, mengelola file komputer, dan berinteraksi dengan komputer. 
- **Shell** adalah  program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi. 
- Aplikasi yang digunakan untuk mengakses CLI adalah **Terminal emulator**. 

- **File system structure** adalah struktur yang mengatur bagaimana data disimpan di dalam sebuah system. Dalam menyusun file dan direktori pada sistem operasi Windows dan user menggunakan struktur yang bentuknya mirip tree atau disebut dengan file system tree. 
![Picture1](https://user-images.githubusercontent.com/113364526/191979262-6a8b991d-2e25-4503-b6cb-374249390a3d.png)

- **Command untuk navigasi** :
 1. Pwd (print working directory) : untuk melihat current working directory (keberadaan saat ini).
 2. Ls (list) : untuk melihat isi file yang ada disebuah direktori.
 3. Cd (Change Directory) : untuk berpindah direktori lain.
- **Manipulasi file dan directory** : 
1. Touch : untuk membuat sebuah file.
2. Mkdir : untuk membuat sebuah direktori.
3. Head : untuk melihat beberapa line awal dari sebuah file text.
4. Tail : untuk melihat beberapa line awal dari sebuah file text. 
5. Cat : untuk melihat isi sebuah file.
6. Cp : mencopy file atau cp-R directory.
7. Mv : untuk memindahkan file atau mv-R directory. Selain itu juga dapat digunakan untuk rename.
8. Rm : untuk menghapus file yang terdiri dari beberapa command yakni : 
    - Rm-R (hapus file). 
    - Rm-d (hapus direktori).

## **Git & Github**
- ### Apa itu git dan github ???
   - Git
     <div align="justify"> adalah aplikasi yang dapat melacak setiap perubahan yang terjadi pada suatu folder atau file. biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif.
   - Github
     <div align="justify"> adalah sebuah layanan cloud yang bisa membantu para pengguna untuk menyimpan,mengelola dan mengembangkan. Didalam github kita bisa mengupload file,membuat file yang mana filenya bisa kita kelola dengan version control system punya github. 
    Jadi perbedaan git dan github ialah
      
- ### Pentingnya menggunakan Git & Github
  <div align="justify"> Dengan menggunakan Git dann Github, kita bisa berkolaborasi mengerjakan proyek yang sama dengan orang lain tanpa harus repot  copy paste folder aplikasi yang terupdate. Selain itu juga, kita tidak perlu menunggu rekan dalam satu tim menyelesaikan program dahulu untuk berkolaborasi. Kita juga bisa membuat file di dalam proyek yang sama atau membuat code di file yang sama dan menyatukannya saat sudah selesai.
 

## **Algoritma**
- **Algoritma** adalah urutan logis untuk memecahkan masalah secara logis dan sistematis. Dengan kata lain, dalam kehidupan sehari - hari kita sudah menerapkan algoritma untuk memecahkan suatu masalah. 
 &nbsp;
- **Manfaat algoritma** : 
1. Membantu menyederhanakan suatu program yang rumit dan juga besar.
2. Mempermudah pembuatan program yang dapat menyelesaikan masalah tertentu.
3. Membantu menyelesaikan suatu masalah dengan logika dan juga sistematis.
- **Contoh algoritma sederhana** : 
Perhitungan Luas Persegi Panjang
1. Masukkan panjang 
2. Masukkan lebar
3. Luas persegi panjang adalah panjang * lebar
4. Tampilkan luas persegi panjang 
- **Penerapan algoritma luas persegi panjang ke dalam bahasa pemrograman C++**

```
#include <iostream>
  using namespace std;
  int main (){
  int p, l;
  cout<<"Masukkan panjang = ";
  cin>>p;
  cout<<"Masukkan lebar= ";
  cin>>l;
  cout<<"Luas Persegi panjang = "; cout<<(p*l)
  }
  ```

- **Penerapan algoritma luas persegi panjang ke dalam bahasa pemrograman javascript**

 ```
let i= 1;

for ( i=1; i<10; i++) {
    if(i%2==0){
    console.log(i);
    }
}
 ```
 
