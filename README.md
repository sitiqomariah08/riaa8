# Aplikasi CRUD Data Buku Menggunakan Java Swing dan PostgreSQL

## Deskripsi UTS
Tugas ini merupakan simulasi Ujian Tengah Semester yaitu membuat aplikasi `CRUD` (Create, Read, Update, dan Delete) data buku dengan atribut `KodeMK`, `SKS`, `NamaMK`, `SemesterAjar` menggunakan Java Swing dan Postgresql. 

## Langkah-langkah
1. Membuat koneksi baru di Java yang disambungkan dengan Postgresql. Klik kanan pada Database yang ada di menu service, lalu new connection dan memilih postgresql.
   
   ![Screenshot 2024-10-08 124749](https://github.com/user-attachments/assets/7e642a2b-2b81-4647-8d1f-2bda9c20eb4a)
   ![Screenshot 2024-10-08 124802](https://github.com/user-attachments/assets/45e5c91a-7792-4d8b-9064-74e01036508b)
   
2. Mengisi dan menyesuaikan dengan database yang telah dibuat. Kemudian pilih public dan finish.

   ![Screenshot 2024-10-08 124824](https://github.com/user-attachments/assets/bfa117af-f7d8-4e8a-acb9-32419f88209c)
   ![Screenshot 2024-10-08 124832](https://github.com/user-attachments/assets/964cffe5-4010-4b27-a528-00982f54916e)
   ![Screenshot 2024-10-08 124841](https://github.com/user-attachments/assets/97f0d0a2-5d26-4dc0-ba7e-00ea82701a5d)

3. Kemudian, membuat library baru untuk mengkoneksikan ke database kita dengan klik kanan pada Library, lalu Add Library dan pilih Postgresql JDBC Driver.

   ![Screenshot 2024-10-08 124850](https://github.com/user-attachments/assets/02a4ca17-039b-4513-851c-37fc9b2716a4)
   ![Screenshot 2024-10-08 124903](https://github.com/user-attachments/assets/def4b722-3ef0-4282-9cc0-607bc90ef0c2)

4. Ini adalah tampilan ketika kita sudah add library kita dengan JDBC Driver Postgresql.

   ![Screenshot 2024-10-08 124912](https://github.com/user-attachments/assets/32ce0497-7ad3-4aad-9c84-402c671bf461)

5. selanjutnya adalah membuat desain Java Swing dengan cara klik kanan pada package yang telah dibuat, lalu pilih Jframe From.

   ![image](https://github.com/user-attachments/assets/e9715e01-6d3d-42d2-b40b-2d0f6652f466)

6. Beri nama pada Jframe From nya, disini saya memberi nama yaitu mahasiswa_uts.

   ![Screenshot 2024-10-08 125100](https://github.com/user-attachments/assets/18312d8b-9fd1-476e-a14e-803b0f1db8f3)

7. Berikut adalah desain yang telah saya buat.

   ![Screenshot 2024-10-08 130258](https://github.com/user-attachments/assets/e044f983-3116-44be-9c1c-357538ab964b)

8. Kemudian, terlebih dahulu saya membuat class DbUtils pada package yang sama, dengan source code berikut ini : 

   ![Screenshot 2024-10-08 125021](https://github.com/user-attachments/assets/ed02d610-f15e-4788-a6fb-1cba99267281)

9. Sebelum lanjut ke tahap selanjutnya, kita harus membuat tabel yang ada di database kita. Berikut adalah query dari pembuatan tabel dalam database saya dengan beberapa atribut yang sudah ditentukan.

    ![Screenshot 2024-10-08 134656](https://github.com/user-attachments/assets/b86d98b8-fb95-40fa-9f6b-6c18053d1247)

10. Berikut adalah source code dari Insert.

    ![image](https://github.com/user-attachments/assets/5f4c8e68-8381-48b8-be2f-94b3a486b303)
    dalam insert kita harus mengisi pertanyaan yang ada, kemudian akan bisa melakukan aksi insert. jika kita mengosongi salah satunya, maka program tidak akan berjalan dan ada pop up peringatannya.

11.  Berikut adalah source code dari Update.

    ![Screenshot 2024-10-08 134933](https://github.com/user-attachments/assets/929fdfda-9f96-43bc-9f67-e7fce0c69da4)
     dalam update kita bisa mengeklik data pada tabel saja, lalu data akan otomatis ke isi pada kolom jawaban. Kemudian kita akan dengan mudah mengganti apa yang perlu diganti, tapi tidak untuk PRIMARY KEY.

12. Berikut adalah source code dari Delete.

    ![image](https://github.com/user-attachments/assets/2555d762-d82a-4ecf-8a5a-8e45b5b64fe6)
    dalam delete ini akan menghapus data yang kita inginkan dan memberikan konfirmasi saat akan menghapus data.

13. Berikut adalah source code dari Tampil/Select.

    ![image](https://github.com/user-attachments/assets/48a87035-28cd-404e-be89-d4a436be9fcd)

14.  Berikut adalah source code dari tbTabelMouseClicked.

    ![Screenshot 2024-10-08 135146](https://github.com/user-attachments/assets/0d79420a-54b8-4d17-8485-9aedbe3aeeb2)

15. Berikut adalah source code dari Clear.

    ![image](https://github.com/user-attachments/assets/a403435e-69c4-4199-861b-01c091b36304)

    dalam source code ini juga ada tambahan code untuk mengkosongkan semua kolom jawaban yaitu dengan Clear yang mengambil dari method bersih berikut ini.

    ![image](https://github.com/user-attachments/assets/ff7acb7c-37cc-4811-b1bc-940fc556afa4)

16. Berikut adalah hasil desain dari yang telah saya buat.

    ![Screenshot 2024-10-08 133329](https://github.com/user-attachments/assets/0591e0b9-6d00-426c-9b2e-2a3159929985)

Semoga penjelasan diatas dapat membantu memahami materi dalam tugas pertemuan 8 UTS mata kuliah Pemrograman Berorientasi Objek ini.










 







   

   
