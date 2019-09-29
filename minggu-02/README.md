# PRAKTIKUM KCC MINGGU 2 #

1. membuat BRANCH

![alt text](IMG2/aa.png)
2. menuju ke brand baru dengan perintah

```git checkout -b edit-minggu-01```

![alt text](IMG2/a.PNG)
3. setelah ke brand baru, lanjutkan perubahan isi README.md

apa itu branch : branch adalah cabang, fungsinya adalah untuk merubah isi project anda bila anda takut jika terjadi kesalahan yang besar, nah di branch tersebuat anda bebas merubah isi project anda, setelah anda yakin kemudian dipush di branc anda dengan perintah

```git push origin edit-minggu-01```

![alt text](IMG2/bb.png)

tidak bisa karena belum di pull, maka gunakan perintah pull

```git pull origin edit-minggu-01```

![alt text](IMG2/bbb.png)

setelah itu kemudian diAdd kemudian commit, baru kemudian diPush di branch yang baru, setelah itu diCek di branch master perubahan pada isi project.

![alt text](IMG2/b1.png)

hanya sampai di keterangan no.2, kemudian lihat di branch edit-minggu-01

![alt text](IMG2/b2.png)

project sampai pada keterangan no 3. nah jika sudah yakin maka di merge agar perubahan sampai pada branch master.

4. merge, kembali ke branch master dahulu dengan peintah

```git checkout master```

```git merge edit-minggu-01```

![alt text](IMG2/c.PNG)

