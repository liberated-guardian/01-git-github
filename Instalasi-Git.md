# Instalasi Git pada Windows  
###### [ [KEMBALI](https://github.com/liberated-guardian/01-git-github) ]  
Sebelumnya download Git Installer terlebih dahulu di [sini](https://git-scm.com/downloads). Setelah itu jangan lupa download *Text Editor* terlebih dahulu, contohnya [Notepad++](https://notepad-plus-plus.org/downloads/) atau [Visual Studio Code](https://code.visualstudio.com/). Jika Git Installer dan Text Editor sudah anda install, maka langsung saja ke cara instalasinya:
1. Setelah download Git, jalankan filenya lalu pada tampilan utama akan ada lisensi, next saja.  
![Gambar Instalasi01](images/1/install01.png)
2. Pilih lokasi instalasi Git, jika ingin di install pada lokasi default maka next saja, jika tidak maka klik *Browse* lalu pilih ingin diinstall dimana.  
![Gambar Instalasi02](images/1/install02.png)
3. Selanjutnya akan disuruh memilih komponen dari Git yang akan diinstall, biarkan seperti default saja lalu next.  
![Gambar Instalasi03](images/1/install03.png)
4. Installer akan memberikan tawaran mengenai folder yang akan dibuat pada start menu windows. Folder yang dibuat dapat diganti namun opsional, klik next.  
![Gambar Instalasi04](images/1/install04.png)
5. Pilih text editor yang akan digunakan, disini saya akan menggunakan VSCode dari Microsoft.  
![Gambar Instalasi05](images/1/install05.png)
6. Pada saat menginstall, akan ditanya apakah ingin mengganti nama Branch atau Cabang utamanya, disini saya memilih Let Git decide karena jika kurang cocok dengan nama yang diberi oleh Git kita dapat menggantinya nanti.  
![Gambar Instalasi06](images/1/install06.png)
7. Setelah itu akan ditanya mengenai cara menggunakan Git, pilihan pertama berarti Git hanya dapat digunakan melalui Bash (aplikasi bawaan dari Git), pilihan kedua berarti Git dapat diakses menggunakan aplikasi bawaan dan aplikasi pihak ketiga. Saya disini menggunakan pilihan kedua, karena saya akan menggunakan Bash dan VSCode untuk mengakses Git.  
![Gambar Instalasi07](images/1/install07.png)
8. Pilih Use bundled openSSH, karena jika memilih opsi kedua anda harus mencari openSSH secara terpisah.  
![Gambar Instalasi08](images/1/install08.png)
9. Pilih OpenSSL library agar mempermudah Git dalam memvalidasi server yang akan diakses, seperti GitHub, GitLab, dll.  
![Gambar Instalasi09](images/1/install09.png)
10. Gunakan CRLF atau pilihan pertama untuk konveksi akhir baris.  
![Gambar Instalasi10](images/1/install10.png)
11. Pilih MinTTY untuk terminal yang akan digunakan oleh Git Bash.  
![Gambar Instalasi11](images/1/install11.png)
12. Pilih Default saja, agar dapat menggunakan fast-forward dan merge.  
![Gambar Instalasi12](images/1/install12.png)
13. Gunakan Git Credential Manager Core, karena itu sudah support cross-platform.  
![Gambar Instalasi13](images/1/install13.png)
14. Disini aktifkan file system caching agar Git dapat bekerja lebih cepat.  
![Gambar Instalasi14](images/1/install14.png)
15. Pada opsi ini, saya tidak menggunakan keduanya, karena masih dalam tahap Experimental, tentunya masih banyak bug.  
![Gambar Instalasi15](images/1/install15.png)
16. Tunggu proses install dari Git hingga selesai.  
![Gambar Instalasi16](images/1/install16.png)
17. Jika sudah, klik finish saja.  
![Gambar Instalasi17](images/1/install17.png)
18. Untuk memeriksa versi, dan untuk validasi apakah Git sudah terinstall kita bisa cek melewati Command Prompt pada Windows. Gunakan perintah `git --version`.
![Gambar Instalasi18](images/1/install18.png)  
Jika sudah muncul versi dari Git yang sudah diinstal dan sesuai dengan Git yang didownload maka bisa lanjut ke [Konfigurasi Git](https://github.com/liberated-guardian/01-git-github/blob/main/Konfigurasi-Git.md).