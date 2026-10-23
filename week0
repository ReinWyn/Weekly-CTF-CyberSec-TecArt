Nama : Made Reindra Aryanatha  
NIM : 260530911019  

Penggunaan Tools yang digunakan UBUNTU  
KATEGORI CTF PILIHAN : FORENSICS  

# Penggunaan WSL  
<img width="1612" height="1007" alt="Screenshot 2026-09-23 212445" src="https://github.com/user-attachments/assets/54649a5b-9448-4f43-8f79-b83a72945d35" />  
Gambar diatas merupakan pengujian WSL menggunakan command line dari linux serta pengujian terhadap python.

# PENYELESAIAN CHALLENGE CTF  
Pertama download file cat.jpg dari challange information. Didalam file cat.jpg ada flag yang harus kita dapatkan dengan menggunakan ExifTool didalam WSL dengan menjalankan perintah `sudo apt install libimage-exiftool-perl -y`
Setelah instalasi ExifTool kita bisa akses `cat.jpg` tersebut menggunakan perintah exiftool yaitu `exiftool cat.jpg`
<img width="1611" height="867" alt="Screenshot 2026-09-23 214755" src="https://github.com/user-attachments/assets/016c0bb3-9774-41d8-a3b5-1a0eaf620d6d" />  
Diatas merupakan gambar setelah melakukan perintah exiftool. Digambar terlihat bahwa terdapat string terselubung yang telah dienkripsi atau diencode, sehingga langkah selanjutnya adalah mengekstrak dan mendekode kode tersebut untuk mendapatkan flag akhir.

Dari gambar diatas kita akan cek bagian lisence dengan perintah `echo "cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9" | base64 -d`  
<img width="1461" height="750" alt="Screenshot 2026-09-23 215509" src="https://github.com/user-attachments/assets/22089392-7ac2-4e7a-8860-efe251519233" />  
Gambar diatas merupakan tampilan setelah perintah `echo "cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9" | base64 -d`. Didalam tampilan terlihat bahwa sudah berhasil mendapatkan flag yaitu picoCTF{the_m3tadata_1s_modified}  

Selama Pengujian dan penugasan CyberSecurity saya mencari saran dan refrensi dari berbagai sumber seperti google dan ai untuk membantu saya lebih mengerti dan juga mendalami tentang perintah perintah dan hal yang harus diketahui untuk CTF.
