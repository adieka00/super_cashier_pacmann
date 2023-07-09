# super_cashier_pacmann
# Tujuan pengerjaan project
Aplikasi ini dibuat dalam rangka memenuhi kebutuhan andi untuk membuat aplikasi kasir untuk tokonya. 

Fitur yang dibutuhkan untuk aplikasi ini adalah:
1. menambahkan barang yang akan dibeli
2. melakukan pengubahan nama barang, jumlah barang dan harga barang
3. menghapus item yang dibeli dan/atau menghapus semua item yang dibeli
4. melakukan pengecekan keranjang belanja
5. melihat total harga belanja dan menambahkan diskon secara otomatis

#Fungsi dan fitur
1. Customer bisa membuat ID transaksi yang dia lakukan.
requirements ini bisa dipenuhi dengan membuat objek yang mewakili setiap transaksi yang dilakukan. let's say trnsct123
kedepannya bisa ditambahi fitur dimana setiap transaksi akan bisa disimpan dalam satu database dan ID transaksi bisa dibuat secara otomatis setiap transaksi
2. Customer bisa menambahkan item dengan fungsi add_item(nama item, jumlah item, harga)
3. mengubah nama item, mengupdate jumlah item dan mengubah harga item. requirements ini bisa dioenuhi dengan menambahkan fungsi update_item_name(nama sebelumnya, nama baru), update_item_qty('nama item', jumlah baru), update_item_price('nama item', harga baru)
4. Customer bisa menghapus item dalam daftar belanja dengan fungsi delete_item('nama item')
5. customer bisa menghapus semua daftar belanja dengan fungsi reset_transaction()
6. fungsi mengecek daftar belanja dengan check_order()
7. fungsi untuk mengecek total belanja dan built-in discount calculator pada fungsi total_price()

#cara menggunakan
1. upload script.py kedalam notebook
2. import script dengan code 

`from script import Transaction`

3. jalankan fungsi sesuai yang dibutuhkan


