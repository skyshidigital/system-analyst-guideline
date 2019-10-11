System Analyst Guideline
====================

### Daftar Isi

- [Penulisan Dokumen](#penulisan-dokumen)
   - [Pedoman Menuliskan Secara Eksplisit Batasan Versi Environment Aplikasi di Business Process](#pedoman-menuliskan-secara-eksplisit-batasan-versi-environment-aplikasi-di-business-process)
   - [Pedoman Menggunakan Huruf Kapital pada Awal Kalimat Pada Business Process](#pedoman-menggunakan-huruf-kapital-pada-awal-kalimat-pada-business-process)
 
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
