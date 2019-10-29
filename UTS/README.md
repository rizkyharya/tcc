# UTS

1. MEMBUAT AKUN DOCKERHUB
![alt text](IMGuts/1.PNG)
2. MEMBUAT FOLDER "RIZH"
```
C:\Users\User> mkdir rizh
C:\Users\User> cd rizh
C:\Users\User\rizh> ls
    Directory: C:\Users\User\rizh
Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----       10/28/2019   9:18 PM             47 Dockerfile
-a----       10/28/2019   9:29 PM            158 RIZH38.html
 ```
 3. ISI FOLDER TERSEBUT PASTIKAN SUDAH ADA "DOCKERFILE"nya, jika belum maka buat file yang isinya script berikut
  
 ```
 FROM nginx:alpine
COPY . /usr/share/nginx/html
 ```