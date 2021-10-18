# LatihanVcs1
# Tutorial menggunnakan git
Apa itu Git?

Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.

## Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut

- git config --global user.name "username" 
- git config --global user.email "email"
![Screenshot (17)](https://user-images.githubusercontent.com/92367765/137684106-a9f87253-d38e-4ad4-95ed-dbfef8516653.png)
## Jalankan perintah git init. untuk membuat repository local
- git init
![Screenshot (18)](https://user-images.githubusercontent.com/92367765/137687267-d0e3d35c-9b2b-4097-95a7-9ade26646c03.png)
## Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
- echo "# belajargit" >> README.md
![Screenshot (19)](https://user-images.githubusercontent.com/92367765/137687709-2c619cf4-aef1-47d4-a007-911c3600a1a2.png)
## Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
- git add README.md
- git add .
![Screenshot (20)](https://user-images.githubusercontent.com/92367765/137688523-ad0903b9-a166-4e9e-9729-896678a405fa.png)
## Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" Dan yang ada di dalam tanda kutip " " itu adalah nama kommentar setiap kita mencommit project
- git commit -m "menambahkan Project"
![Screenshot (21)](https://user-images.githubusercontent.com/92367765/137689430-97485945-3bbb-4279-bfa2-d089f0fa7d84.png)
## Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
- git remote add origin https://github.com/ArjunSyah/LatihanVCS.git
![Screenshot (22)](https://user-images.githubusercontent.com/92367765/137690964-a5592d17-10f7-4e2e-8bc7-82366c742233.png)
## Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push, Perintah ini akan meminta Username dan Password pada akun github mu
- git push -u origin master
![Screenshot (23)](https://user-images.githubusercontent.com/92367765/137691313-92e933ea-3a6f-42f3-9ed7-3695b72ff348.png)
- Selesai
# TRIMAKASIH 
