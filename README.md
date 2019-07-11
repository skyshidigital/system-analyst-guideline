System Analyst Guideline
====================

### Daftar Isi

- [Penulisan Dokumen](#penulisan-dokumen)
   - [Pedoman Menuliskan Secara Eksplisit Batasan Versi Environment Aplikasi di Proses Bisinis](#pedoman-menuliskan-secara-eksplisit-batasan-versi-environment-aplikasi-di-proses-bisnis)
 
 ### Penulisan Dokumen
 #### Pedoman Menuliskan Secara Eksplisit Batasan Versi Environment Aplikasi di Proses Bisnis
 Penulisan Proses Bisnis yang akan dideliver ke dokumen UAT ditulisakan penjelasan secara eksplisit mengenai versi environment sebuah aplikasi 
 - Menuliskan batasan pengujian versi environment sebuah aplikasi
 - Menuliskan batasan deployment versi environment sebuah aplikasi, seperti :
  - Menuliskan support minimum dan maksimal versi android.
  - Menuliskan support minimum dan maksimal versi IOS.
  - Menuliskan support minimum dan maksimal versi browser.
  - Menuliskan support platform OS yang digunakan (Windows, linux, mac, 32 bit, 34 bit dll )
  - Menuliskan support untuk dekstop / mobile / tablet. 
- <p align="justify">Ketika dilakukan deployment, mendapat laporan bug dari pihak CS atau Client maka lakukan pengecekan mengenai bug tersebut dan cek dokumen yang sudah dibuat.</p>
- <p align="justify">Apabila batasan versi environment aplikasi sudah didefine di Proses Bisnis dan UAT tetapi masih terjadi bug maka hotfix wajib dilakukan.</p>
- <p align="justify">Apabila batasan versi environment aplikasi belum didefine di Proses Bisnis dan UAT, maka cek kembali untuk mempertimbangkan prosentase impact yang akan terjadi pada user dan device (GA atau firebase), apabila impact yang akan terjadi tinggi maka diskusikan terlebih dahulu untuk pricing hotfix priority dan apabila yang terkena impact tindak tinggi maka masuk ke sprint berikutnya.</p>
