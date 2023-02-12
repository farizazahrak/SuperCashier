# Super Cashier 
##  Python Project - Fariza Zahra Kamilah - ADS 

### Objectives 
Membuat sistem kasir self-service agar customer bisa langsung memasukan produk yang ingin dibeli, jumlah item yang dibeli, dan harga item, serta fitur-fitur lainnya. Program ini juga dimaksudkan agar pembeli yang tidak berada di kota tersebut bisa tetap bisa membeli di supermarket milik Andi. 

### Feature Requirements and flowchart 
1. Membuat proses untuk membuat ID transaksi customer 
2. Membuat proses untuk memasukkan nama produk, jumlah, dan harga
3. Membuat proses untuk melakukan update detail produk /penghapusan item produk jika ada kesalahan 
4. Membuat proses untuk menampilkan daftar pesanan 
4. Membuat proses jika ingin melakukan pembatalan pembelian hanya pada beberapa item 
5. Mereset semua transaksi 
6. Membuat proses untuk mengecek apakah data yang diinput sudah benar 
7. Membuat proses untuk menghitung jumlah total belanja (tanpa dan dengan diskon). 

### Code explanation 
#### a. init() 
Merupakan fungsi inisiasi untuk membuat class product/ membuat ID transaksi customer. 
![image](https://user-images.githubusercontent.com/125171866/218322608-230d99ee-4986-41aa-95d0-276aae502fbb.png)

#### b. add_item() 
Merupakan metode/fungsi untuk memasukkan detail produk yang dibeli seperti nama produk, jumlah, dan harga 
![image](https://user-images.githubusercontent.com/125171866/218322619-3da4f935-4664-4f47-ac4b-6786aa600bcd.png)

#### c. update_item() 
Merupakan metode/fungsi untuk meng-update atau mengubah detail produk yang dipesan 
![image](https://user-images.githubusercontent.com/125171866/218322625-1aedb2d2-f640-4a6d-a1d5-3f3aede3a082.png)

#### d. show_order() 
Merupakan metode/fungsi untuk menampilkan produk-produk yang dibeli customer 
![image](https://user-images.githubusercontent.com/125171866/218322646-c2bd4fde-5783-41b3-b49f-b78aa7570edb.png)

#### e. delete_item() 
Merupakan metode/fungsi jika ingin melakukan pembatalan pembelian hanya pada beberapa item 
![image](https://user-images.githubusercontent.com/125171866/218322651-48238737-067b-4bdc-9977-3027f58be1cc.png)

#### f. reset_transaction() 
Merupakan metode untuk menghapus/membatalkan semua transaksi
![image](https://user-images.githubusercontent.com/125171866/218322658-9b401674-3914-4221-93a2-3eeaca93cbc7.png)

#### g. check_order dan total_price()
Merupakan fungsi untuk mengecek apakah data yang diinput sudah sesuai kemudian total_price digunakan untuk melihat total harga yang perlu dibayarkan oleh customer. 

![image](https://user-images.githubusercontent.com/125171866/218322667-86bfec57-2e5a-4ba4-b278-aa06435b765f.png)
![image](https://user-images.githubusercontent.com/125171866/218322705-519fc384-5a24-4f90-a4f0-fb756907e979.png)

### Strength and Weakness 
1. Strength: Alur program sederhana dan dapat customize barang sesuai dengan keinginan customer 
2. Weakness: Agak sulit diterapkan sekarang pada skala yang lebih besar 

### Things might do in the future 
1. Membuat list database kode barang seperti yang dilakukan cashier-cashier saat ini. 



