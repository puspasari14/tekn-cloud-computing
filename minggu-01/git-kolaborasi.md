### fork
Fork yaitu membuat clone dari suatu repo di GitHub milik upstream author, diletakkan ke milik kontributor. Fork hanya dilakukan sekali saja. Upstream author adalah rohmapuspa.

untuk melakukan fork klik sisi kanan 

![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/fork.jpg "awal")

akun yang digunakan puspasari14 dan yang dilakukan fork adalah file rohma

![alt text](https://github.com/puspasari14/tekn-cloud-computing/blob/master/minggu-01/fork1.jpg "dua")

#### melakukan clone ke lokal
```
C:\partcc\tekn-cloud-computing>git clone https://github.com/puspasari14/rohma
Cloning into 'rohma'...
remote: Enumerating objects: 11, done.
remote: Counting objects: 100% (11/11), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 11 (delta 1), reused 11 (delta 1), pack-reused 0
Unpacking objects: 100% (11/11), done.
```

### konfigurasi
konfigurasikan repo lokal kontributor. Pada kondisi saat ini, di komputer lokal sudah terdapat repo rohma yang berada pada direktori dengan nama yang sama.

 Konfigurasi repo upstream harus dibuat.

```
C:\partcc\tekn-cloud-computing\rohma>git remote -v
origin  https://github.com/puspasari14/rohma (fetch)
origin  https://github.com/puspasari14/rohma (push)
```
ada upstream
```
C:\partcc\tekn-cloud-computing\rohma>git remote add upstream https://github.com/rohmapuspa/rohma
```
hasil
```
C:\partcc\tekn-cloud-computing\rohma>git remote -v
origin  https://github.com/puspasari14/rohma (fetch)
origin  https://github.com/puspasari14/rohma (push)
upstream        https://github.com/rohmapuspa/rohma (fetch)
upstream        https://github.com/rohmapuspa/rohma (push)
```

### mengirimkan pull rrequest
