#Latihan1

PERINTAH DASAR GIT

1. git init, perintah untuk membuat repository local

2. git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.

3. git commit, perintah untuk menyimpan perubahan kedalam database git.

4. git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.

5. git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

6. git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).

Langkah-Langkah Menggunakan Git.

- Buka Drive yang ingin dipakai, semisal Drive D jalankan dengan perintah cd /D
 
  ![whatsapp image 2019-01-26 at 21 35 09 1](https://user-images.githubusercontent.com/46749500/51788862-4a3fc080-21b5-11e9-8ff7-0af470b2a128.jpeg)

- Buat directory dengan printah "mkdir" sebagai contoh : directory Pemograman1
 
  ![whatsapp image 2019-01-26 at 21 35 09 7](https://user-images.githubusercontent.com/46749500/51789064-cdfaac80-21b7-11e9-852c-7d65af402999.jpeg)


- Buka directory Pemograman1 dengan perintah cd Pemograman1

  ![whatsapp image 2019-01-26 at 21 35 09 9](https://user-images.githubusercontent.com/46749500/51789075-026e6880-21b8-11e9-8669-41da792c926f.jpeg)


- Buatlah directory project praktikum pertama denagan nama latihan1 dan kemudian masuk ke dierectory tersebut, directory aktif akan menjadi : d\pemograman1\latihan1

  ![whatsapp image 2019-01-26 at 21 35 09 5](https://user-images.githubusercontent.com/46749500/51789100-32b60700-21b8-11e9-90eb-0068b868a338.jpeg)


- Jalankan perintah git init untuk menjalankan repository local.
- Repository baru berhasil di analisasi, dengan terbentuknya satu directory hidden dengan nama .git
- Pada direktori tersebut, semua perubahan pada working directory akan disimpan
  
  ![whatsapp image 2019-01-26 at 21 35 09 3](https://user-images.githubusercontent.com/46749500/51789149-a5bf7d80-21b8-11e9-890f-5e6654d7fae4.jpeg)


- Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md
- Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
- Disini kita akan coba buat satu file bernama README.md (text file)
  
  ![whatsapp image 2019-01-26 at 21 35 09 2](https://user-images.githubusercontent.com/46749500/51789195-df908400-21b8-11e9-9b9c-374d0e9c4fdb.jpeg)


- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md
- File README.md berhasil dibuat.
  
  ![whatsapp image 2019-01-26 at 21 35 09](https://user-images.githubusercontent.com/46749500/51789209-0b136e80-21b9-11e9-9811-383b98c3b17c.jpeg)


- Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"
  
  ![whatsapp image 2019-01-26 at 21 35 09 12](https://user-images.githubusercontent.com/46749500/51789224-2e3e1e00-21b9-11e9-83a7-dcefa69d784b.jpeg)


- Menambahkan remote repository.
- Remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak   user
- Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url] 
  
  ![whatsapp image 2019-01-26 at 21 35 09 8](https://user-images.githubusercontent.com/46749500/51789245-634a7080-21b9-11e9-897f-a8e69c421a39.jpeg)


- Mengirim perubahan ke server dengan perintah git push -u origin master
- Perintah ini akan meminta memasukkan username dan password pada akun github.com
  
  ![oo](https://user-images.githubusercontent.com/46749500/51789278-ec61a780-21b9-11e9-942d-a1ae699c8848.jpg)


- Untuk mengirim perubahan jalankan perintah git push -u origin master
- Kemudian jalankan perintah git add README.md
  
  ![whatsapp image 2019-01-26 at 21 35 09 10](https://user-images.githubusercontent.com/46749500/51789334-609c4b00-21ba-11e9-81fe-89ad43b4d9ee.jpeg)
![hiji](https://user-images.githubusercontent.com/46749500/51789375-da343900-21ba-11e9-8363-9e1aecb08924.jpg)

- Kemuidan lihat perubahannya pada laman github.com



