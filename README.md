# ShushMe
Google Places API demo app

## Screenshots

<img src="https://user-images.githubusercontent.com/22130552/30463632-0aa9a892-99f7-11e7-8504-ec9eca459051.png" width="290" height="515"/> <img src="https://user-images.githubusercontent.com/22130552/30463643-13a4a082-99f7-11e7-9bd2-6d68ee396b85.png" width="290" height="515"/>

</br>

<img src="https://user-images.githubusercontent.com/22130552/30463644-13aa39ca-99f7-11e7-8a99-2aad859db56f.png" width="290" height="515"/> <img src="https://user-images.githubusercontent.com/22130552/30463646-1536540e-99f7-11e7-97d3-4c9a7fa39dc4.png" width="290" height="515"/>

</br>

<img src="https://user-images.githubusercontent.com/22130552/30463645-1410294c-99f7-11e7-9c27-e4365117bffb.png" width="290" height="515"/> <img src="https://user-images.githubusercontent.com/22130552/30463646-1536540e-99f7-11e7-97d3-4c9a7fa39dc4.png" width="290" height="515"/>

</br>

<img src="https://user-images.githubusercontent.com/22130552/30464004-3371e076-99f9-11e7-8f19-c92c3caa49f3.png" width="290" height="515"/> <img src="https://user-images.githubusercontent.com/22130552/30463950-f2ff9b28-99f8-11e7-91d3-a19e72dabacb.png" width="290" height="515"/>

</br>

<img src="https://user-images.githubusercontent.com/22130552/30464949-b88fe514-99fe-11e7-9f60-00ef6c04b08d.png" width="290" height="515"/> <img src="https://user-images.githubusercontent.com/22130552/30464881-61ee487c-99fe-11e7-8a65-a0e587e8d7d8.jpeg" width="290" height="515"/>

</br>

## Penjelasan 

Ketika pertama kali aplikasi dijalankan, akan muncul switching Enable Geofences yang bisa di enable dan di disable dan juga Add New Location tetapi belum bisa difungsikan.
Pada commitan GoogleApiClient, ditambahkan Location Permission dimana itu digunakan untuk mendapatkan ijin user apakah aplikasi boleh mengakses aplikasi secara otomatis. Pada commitan ini Add New Location jika diklik akan muncul notifikasi Location Permission Granted.
Pada commitan PlacePicker, ditambahkan kode untuk mengakses lokasi kita dan juga memfungsikan Add New Location. Jadi saat kita klik Add New Location, nanti akan otomatis menunjukkan tempat kita saat ini, kita juga bisa menyimpan lokasi tersebut dengan menu pilih lokasi ini yang ada tepat dibawah map.
Pada commitan GetPlaceById, ditambahkan geofence yang berfungsi untuk memunculkan gambar saat kita menambahkan lokasi tersebut dalam list lokasi kita.
Pada commitan SilentMode, ditambahkan pengaturan untuk notifikasi yang ditampilkan. Notifikasi tersebut muncul jika kita berada di posisi yang kita pilih.

</br>

## Identitas

Nama : Erron Lolha Aprillia </br>
Kelas : XII RPL 2 </br>
No : 13 </br>
NIS : 4705/1424.070 </br>
Sekolah : Telkom School Malang </br>
