# PRAKTIKUM KCC MINGGU 1

##### "RIZKY HARYA / 175410001"

Langkah 1 pastikan Github sudah terinstal, dapat di cek di CMD
dengan perintah
```git --version```

![alt text](1.png)

jika belum, dapat diinstal di https://git-scm.com/downloads

Langkah 2 konfigurasi Git
buka cmd dan ketikan perintah
```
git config --global user.name "Nama Anda di GitHub"
git config --global user.email email@domain.tld
```
![alt text](2.png)

Langkah 3 Kelola repo anda
buka akun Github anda kemudian klik bagian **+** New repository
![alt text](new-repo.png)
kemudian namai repo anda lalu klik **create repository**
![alt text](3.png)
setelah itu clone repo anda menggunakan perintah
```git clone https://github.com/rizkyharya/tcc.git```
kemudian membuat file bernama **README.md**
kelola file tersebut sesuai keinginan anda

kemudian di Push
dengan perintah
```
git add -A
git status
```
![alt text](push1.PNG)
```
git commit -m "Add: isi README.md"
```
![alt text](push2.PNG)
```
git push origin edit-readme-1
```
![alt text](push3.PNG)

# PRAKTIKUM KCC MINGGU 2 17/09/2019

##### "RIZKY HARYA / 175410001"

Mengubah Isi dengan Branching and Merging
langkah :
1. membuat branch baru dengan perintah
```git checkout -b edit-minggu-01```
![newbranch](a.PNG)
2. lakukan perubahan pada master
3. add dan commit ke branch baru
![newbranch](b.PNG)
4. kembali ke repo master
![newbranch](c.PNG)

mencoba lakukan prubahan