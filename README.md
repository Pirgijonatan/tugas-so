1.
a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : 


![Screenshot 2025-03-25 141835](https://github.com/user-attachments/assets/743eb8a0-e7ca-4544-aa42-84322c6e5b0f)


membuat nama
ini contoh menambahkan text echo “Profile dari .bash_profile” 

![Screenshot 2025-03-25 142141](https://github.com/user-attachments/assets/ad7b1219-4b3f-4e86-a41a-33c4507b0bf9)
![Screenshot 2025-03-25 142019](https://github.com/user-attachments/assets/426e6211-5cc9-41cc-b0f2-b67cbe9d989b)

menjalankan su

![Screenshot 2025-03-25 142825](https://github.com/user-attachments/assets/68d100a0-5516-404f-8d9d-18db29096b82)

menjalankan -su

![Screenshot 2025-03-25 142857](https://github.com/user-attachments/assets/0d35d9f2-e549-4048-b5bf-2874479799d1)

perbedaan antara dua su adalah su cuman menampilkan profile dari bash.profle sedangkan -su membuat linux menjadi warna merah atau menjadi mode root

2. Prompt String (PS)

   mengubah menggunakan > jadi seperti ini:

   ![Screenshot 2025-03-25 150148](https://github.com/user-attachments/assets/f7886116-908c-41ad-acd8-d7dca97e149e)

3. membuat text logout
 ini tampilan ketika mau keluar/logout

menggunakan source


![Screenshot 2025-03-25 150636](https://github.com/user-attachments/assets/67c53148-917a-4670-b8b3-b6a6ca515529)

4. Bash script
  membuat script ps.sh
cara membuat ketik nano ps1.sh ps2.sh ps3.sh ini langsung kebuat 3 script

menjalankan hasil script
./p1.sh ; ./p3.sh ; ./p2.sh

![Screenshot 2025-03-25 150955](https://github.com/user-attachments/assets/591301f2-f697-4f4b-9101-004dfa5f92ac)

./p1.sh &

![Screenshot 2025-03-25 151016](https://github.com/user-attachments/assets/c5e52518-44db-4df7-b20d-ef8b19d89b84)

 ./p1.sh $ ./p2.sh & ./p3.sh &
 
 ![Screenshot 2025-03-25 151117](https://github.com/user-attachments/assets/dd99d394-721c-45e0-882a-fcd543748309)


5.jobs
menggunakan ps x


![Screenshot 2025-03-25 151653](https://github.com/user-attachments/assets/8ee4a31c-01d0-47e2-a389-ba7a24abff15)

menggunakan kill

![Screenshot 2025-03-25 151658](https://github.com/user-attachments/assets/e596eb14-471f-4a35-9571-7be088be3e19)

