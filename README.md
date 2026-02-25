# Shoping-Chart-Experiment-Dwi-012
DWI PEBRIYANTO PRADANA | 2409116012 | SISTEM INFORMASI A 2024


# EKSPERIMEN 5: Test Cart Operations
<div align="justify">
Pada Repository ini akan dilakukan pengujian pada Aplikasi Shopping Cart, yaitu aplikasi sederhana berbasis Flutter yang mengimplementasikan fitur keranjang belanja secara langsung di dalam aplikasi. pada aplikasi ini pengguna dapat menambahkan produk ke dalam keranjang, melihat daftar barang yang telah dipilih, mengubah jumlah pembelian, menghapus barang di keranjang, serta melihat total harga yang otomatis diperbarui sesuai dengan perubahan yang dilakukan.
</div>
<br>

Pengujian yang dilakukan antara lain:
- Add to cart from product list
- Show cart items dengan quantity
- Update quantity (+/-)
- Remove items from cart
- Display total price correctly

kemudian menambahkan fitur atau kode tambahan:
- Search/Filter - Search products by name
- Categories - Filter products by category
- Checkout Page - Order summary + form

# Pengujian
### Add to cart from product list
<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/162b8c43-a7fd-40d5-b016-7bb3e9aaa0e7" />

Tampilan awal program menampilkan pilihan produk yang bisa ditambahkan ke keranjang untuk dibeli.
<br>


<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/344c31db-9f6c-4bb9-92e7-826947fcc392" />

Setelah menekan tombol add pada produk yang dipilih, terlihat muncul angka pada keranjang di pojok kanan atas.
<br>

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/0b622e35-b1b0-461b-abdc-68f9db513706" />

Saat menekan keranjang dipojok kanan atas maka akan masuk ke menu keranjang yang berisi produk yang ditambahkan sebelumnya, contohnya disini terdapat laptop gaming sebanyak 3.

### Show cart items dengan quantity
<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/50359cec-a1fd-403c-83dc-3cb98806d264" />

jika menambahkan jenis produk yang berbeda keranjang akan menampikan angka sesuai banyak jenisnya contohnya jika menambah laptop gaming, smartphone, dan wireless headphone maka keranjang akan menampilkan angka 3.
<br>

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/788b26bb-3e71-4f55-a82a-ad03b3d1084e" />

terlihat produk yang ditambahkan sudah muncul di keranjang.

### Increase quantity
<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/e2ef9189-0f85-473f-877d-69a38bdfce1f" />

jika ingin menambahkkan quantitas produk di dalam keranjang bisa menekan tombol "+" sesui produk yang di inginkan. contohnya gmbr diatas menambahkan wireless headphone yang awalnya satu menjadi dua total harga pun jdi berubah yang awalnya 54500000 menjadi 56000000.

### Update quantity (+/-)
<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/29f28f4f-464e-4b74-92e7-dcdb325975f0" />

jika ingin mengurangi quantitas produk bisa menekan tombol "-" pada produk yang ingin dikurangi. contohnya pda gambar mengurangi banyak laptop gaming menjadi 1, sehingga awalnya total harga 56000000 menjadi 24500000.
<br>

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/a8a78424-7fa4-4989-8186-eb2984cfbdb4" />

Produk juga bisa dihapus dengan menekan tombol "-" sesuai produk yng diinginkan hingga quantitasnya 0.

### Remove items from cart
<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/0c321428-bc20-4e68-a576-2ff1d07d5b1a" />

jika ingin langsung menghapus semua barng di keranjang, bisa menekan tombol tong sampah dipojok kanan atas. setelah menekan tombol tersebut akan muncul pesan untuk memastikan pakah benar-benar ingin mengosongkan keranjang, jika tidak silahkan tekan cancel jika tetap ya maka tekan clear.
<br>

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/d8bc774c-0972-433b-a84e-b5784d5d06ff" />

setelah menekan clear maka semua produk di keranjang akan hilang dan logo tong sampah di pojok kanan juga hilang.

### Display total price correctly
<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/788b26bb-3e71-4f55-a82a-ad03b3d1084e" />

terlihat aplkasi sudah menampilkan total harga yanng harus dibayar
# Fitur atau Kode Tambahan
### Search/Filter
<img width="200" height="1094" alt="image" src="https://github.com/user-attachments/assets/ef973dc2-e187-46e9-8ca1-d174c4b88bd1" />

Pada gambar diatas ditambahkan fitur Seaching untuk mencari nama barang dan filtering berdasarkan kategorinya

### Categories
<img width="200" height="643" alt="image" src="https://github.com/user-attachments/assets/438b7a45-6d71-487e-999e-71f70d94464b" />

Kode diatas membuat kategori untuk produk-produk yang tersedia, contohnya electrionic dan accesoris. nantinya kategori ini dapat membantu dalam proses filtering produk.

### Checkout Page
<img width="200" height="1072" alt="Cuplikan layar 2026-02-24 114201" src="https://github.com/user-attachments/assets/97a345df-4cea-4a9b-8194-5a5beaa2614b" />

Checkout page muncul ketika sudah memasukan barang ke keranjang dan menekan tombol checkout. pemesan akan diminta isi nama, alamat dan nomor telpon setelah itu menekan tombol place order.
<br>


<img width="200" height="1072" alt="image" src="https://github.com/user-attachments/assets/e646ef42-7f99-4a34-bb47-525f5e97db6b" />

setelah menekan tompol place order akan muncul order success yang menandakan transaksi berhasil.

### Menambah Produk
<img width="400" height="643" alt="image" src="https://github.com/user-attachments/assets/86661e6c-46c4-4a9e-ad27-850ae886f28c" />

Kode diatas menambahkan produk yaitu Mic dan juga Keyboard pada file product_list_page.dart
<br>


<img width="200" height="901" alt="image" src="https://github.com/user-attachments/assets/aca7a303-ebfd-4bad-8695-1e52c5805fcf" />

Terlihat produk yang ditambahkan sudah muncul pada gambar

