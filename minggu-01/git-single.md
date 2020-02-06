### Latihan 
instal berhasil 

```
C:\partcc>git --version
git version 2.21.0.windows.1
```

#### Konfigurasi git
##### dikonfigurasikan email dan username yang digunakan pada git hub


`C:\partcc\tekn-cloud-computing>git config --global user.name "puspasari14"`

`C:\partcc\tekn-cloud-computing>git config --global user.email "puspasaridiananggraeni@gmail.com"`

### menjalankan git bisa dengan gui atau bash 
untuk bash seperti pada gambar dibawah ini
git bash :

    ![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/2.jpg "git bash")

git gui :

    ![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/4.jpg "git gui")

### mengelola repo akun sendiri 
#### membuat repo

membuat repository baru dengan cara mengklik button tambah pada side bar kanan

![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/new%20repo.jpg "new repo")
#### create repository
kemudian akan dialihkan ke halaman create reppository
![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/repo%20create.jpg "create repo" )

kemudian klik create reposiory maka sudah selesai membuat repsitory
![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/jadi%20repo.jpg "repo jadi")

dapat diakses dengan menggunakan url ini
[url github](https://github.com/puspasari14/tekn-cloud-computing)
#### clone
perintah untuk melakukan clone ke lokal 

`C:\partcc>git clone https://github.com/puspasari14/tekn-cloud-computing.git`

maka akan menjalankan seperti dibawah ini 
```
Cloning into 'tekn-cloud-computing'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done. 
```

clone selesai ketika sudah ada `done`

### mengelola akun organisasi

![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/organisasi.jpg "organisai")

### melakukan push pada file git-single.md

```
C:\partcc\tekn-cloud-computing>git add minggu-01/git-single.md

C:\partcc\tekn-cloud-computing>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   minggu-01/git-single.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        minggu-01/rangkuman-cloud-computing.md


C:\partcc\tekn-cloud-computing>git commit -m "s"
[master aa23e85] s
 1 file changed, 4 insertions(+), 2 deletions(-)

C:\partcc\tekn-cloud-computing>git push origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 435 bytes | 87.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/puspasari14/tekn-cloud-computing.git
   7f3ad00..aa23e85  master -> master
```














