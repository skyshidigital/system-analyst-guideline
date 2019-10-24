### PT. Skyshi Digital Indonesia
##### Jl. Tampomas No. 9, Trihanggo, Kec. Gamping,
##### Kab. Sleman, Daerah Istimewa Yogyakarta, Indonesia, 55291.
##### Phone : (0274) 4547428, Email : hello@skyshi.com 

# System Analyst Guideline

## Daftar Isi

- [Penulisan Dokumen](#penulisan-dokumen)
   - [Pedoman Menuliskan Secara Eksplisit Batasan Versi Environment Aplikasi di Business Process](#pedoman-menuliskan-secara-eksplisit-batasan-versi-environment-aplikasi-di-business-process)
   - [Pedoman Menggunakan Huruf Kapital pada Awal Kalimat Pada Business Process](#pedoman-menggunakan-huruf-kapital-pada-awal-kalimat-pada-business-process)
   - [Pedoman Konsistensi Penulisan Role Pengguna Pada Flow Business Process](#pedoman-konsistensi-penulisan-role-pengguna-pada-flow-business-process)
   - [Pedoman Penulisan Soft Delete dan Edit pada Business Process](#pedoman-penulisan-soft-delete-dan-edit-pada-business-process)
 
 ### Penulisan Dokumen
 #### Pedoman Menuliskan Secara Eksplisit Batasan Versi Environment Aplikasi di Business Process
 Penulisan Business Process yang akan dideliver ke dokumen UAT ditulisakan penjelasan secara eksplisit mengenai versi environment sebuah aplikasi 
 - Menuliskan batasan pengujian versi environment sebuah aplikasi
 - Menuliskan batasan deployment versi environment sebuah aplikasi, seperti :
   - Menuliskan support minimum dan maksimal versi android.
   - Menuliskan support minimum dan maksimal versi IOS.
   - Menuliskan support minimum dan maksimal versi browser.
   - Menuliskan support platform OS yang digunakan (Windows, linux, mac, 32 bit, 34 bit dll )
   - Menuliskan support untuk dekstop / mobile / tablet. 
- Ketika dilakukan deployment, mendapat laporan bug dari pihak CS atau Client maka lakukan pengecekan mengenai bug tersebut dan cek dokumen yang sudah dibuat.
- Apabila batasan versi environment aplikasi sudah didefine di Business Process dan UAT tetapi masih terjadi bug maka hotfix wajib dilakukan.
- Apabila batasan versi environment aplikasi belum didefine di Business Process dan UAT, maka cek kembali untuk mempertimbangkan prosentase impact yang akan terjadi pada user dan device (GA atau firebase), apabila impact yang akan terjadi tinggi maka diskusikan terlebih dahulu untuk pricing hotfix priority dan apabila yang terkena impact tindak tinggi maka masuk ke sprint berikutnya.

#### Pedoman Menggunakan Huruf Kapital pada Awal Kalimat Pada Business Process
Pedoman yang harus diperhatikan dalam penulisan font size pada dokumen Business Process sebagai berikut :
- Perhatikan penulisan pada awal kalimat harus dituliskan menggunakan huruf kapital
- Perhatikan kerapian dan konsistensi setiap awal kalimat harus menggunakan huruf kapital, agar dokumen Business Process lebih profesional dan rapi 

#### Pedoman Konsistensi Penulisan Role Pengguna Pada Flow Business Process
Pedoman penulisan role pengguna pada flow business process harus konsistensi seperti berikut : 
- Menuliskan role stakeholeder yang terlibat.
- Jangan menggunakan kata `user` karena terlalu general.
- Mengganti role `user`dengan stakeholder yang terlibat, Contoh : Admin, Supervisor, Custpmer dll.
- Semua aktivitas harus dimulai dengan narasi siapa stakeholder yang terlibat, Contoh : Customer melakukan login di form login.
- Jika terdapat stakeholder yang terlibat dalam 1 role lebih dari 1 stakeholder, maka dituliskan dengan tanda baca `/` untuk menjelaskan semua yang terlibat pada role tersebut, Contoh : Admin/Customer dapat melakukan login pada form login.

#### Pedoman Penulisan Soft Delete dan Edit pada Business Process
Pedoman dalam penulisan soft delete dan edit pada business process, sebagai berikut ini :
- Jika terdapat flow delete, maka pada business process diberikan beberapa optional delete permanen dengan penjabaran alasan dan soft delete beserta penjabaran penjelasan detail.
- Jika terdapat delete, dituliskan impact relasi data yang akan berpengaruh ketika dilakukan delete dan semua relasi akan terhapus semua ataupun ada pemindahan data.
- Jika terdapat edit, maka tuliskan field apa yang dapat diedit dan yang tidak dapat diedit
- Tuliskan impact dan relasi data yang berpengaruh ketika dilakukan edit data.
