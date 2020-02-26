## aditya40.github.io

## _Git Workflow_

### _Git Add New Project_

```` $ git init ```` 
###### _Inisiasi git repository_
###### _User membuat file untuk mengisi git repository_

```` $ git remote add origin github https://github.com/aditya40/aditya40.github.io.git ````
######  _Membuat user terhubung ke remote repository lokal ke remote server_

```` $ git add . ````
###### _Untuk menempatkan semua file ke stage area

```` $ git add index.html ```` 
###### _Untuk menempatkan 1 file ke area_

```` $ git status ```` 
###### _Menampilkan daftar file yang berubah bersama dengan file yang ingin ditambahkan atau dicommit_

```` $ git commit -m "isi dengan keterangan commit" ````
###### _Digunakan untuk melakukan commit pada perubahan ke head_

```` $ git config --global user.name ````
###### _Masukkan username dari pemilik repository_

```` $ git config --global user.email ````
###### _Masukkan email dari pemilik repository_

```` $ git push origin master ````
###### _Digunakan untuk mengirim file yang telah dibuat dan tersimpan di git repository lokal ke repository github


### _Git Existing Project_

```` Open Site [Username].github.io > Setting > Manage Acces > Invite Collaborator ````
###### _Memberikan hak akses untuk user lain mengelola repository_

```` $ git clone https://github.com/AlvinKendra/rickyalvin.github.io.git ````
###### _digunakan untuk checkout repository atau mendapatkan file repository user lain_

````$ git add . ````
###### _Untuk menempatkan semua file ke stage area

```` $ git add index.html ```` 
###### _Untuk menempatkan 1 file ke area_

```` $ git checkout "nama branch" ````
###### _Digunakan untuk membuat branch atau berpindah ke branch lain nya_

```` $ git status ```` 
###### _Menampilkan daftar file yang berubah bersama dengan file yang ingin ditambahkan atau dicommit_

```` $ git commit -m "isi dengan keterangan commit" ````
###### _Digunakan untuk melakukan commit pada perubahan ke head_

````$ git push origin "nama branch" ````
###### _Digunakan untuk mengirim file yang telah dibuat dan tersimpan di git repository lokal ke repository github_

#### _lakukan perubahan pada Vs Code_
###### * _incoming: melakukan perubahan yang ditetapkan oleh request_
###### * _current: menetapkan perubahan yang dimiliki repository_
###### * _both: menetapkan perubahan pada keduanya_

#### _Ulangi Langkah Add,Comit,Config,Push_

```` $ git rebase  "nama branch" ````
###### _jika terjadi kesalahan pada file yang telah di commit_

```` $ git merge "nama branch" ````
###### _mengambil dan menggabungkan perubahan pada branch dan branch aktif_

```` $ git ignore ````
###### _GIT yang bertujuan untuk mengabaikan perubahan pada file atau folder yang sesuai dengan kriteria yang ada didalam file .gitignore. File atau folder yang didaftarkan pada file .gitignore tersebut tidak akan ter-record ke dalam GIT ketika ada perubahan_
