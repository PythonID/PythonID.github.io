# Selamat datang Kontributor :fireworks:
Halaman ini berisi panduan bagaimana cara kamu dapat ikut berkontribusi pada repository ini. Hal yang kamu dapat lakukan adalah:
1. Membuat & Membantu menjawab pertanyaan yang terdapat pada [Issue](https://github.com/PythonID/PythonID.github.io/issues?q=is%3Aissue+is%3Aopen+)
2. Memecahkan masalah berdasarkan [Issue](https://github.com/PythonID/PythonID.github.io/issues?q=is%3Aissue+is%3Aopen+) yang ada, dan melakukan [Pull Request](https://github.com/PythonID/PythonID.github.io/compare)

## Membuat Issue
Buat issue berdasarkan issue template yang tersedia atau jika tidak ada, dapat dengan format markdown sebagai berikut :
```
## Kategori issue
Bisa berisi Ide/Masalah/Pertanyaan

## Judul ide / masalah / pertanyaan
Ceritakan tentang ide/masalah/pertanyaan kamu pada bagian ini secara ringkas dan jelas

## Sertakan Screenshot (Opsional)
Unggah screenshot ataupun gambar yang berkaitan dengan ide/masalah/pertanyaan yang ingin kamu bahas.
```

## Membuat Pull Request
Untuk membantu berkontribusi pada repository ini, hendaknya kita melakukan pull request dengan sebelumnya melakukan Fork repository pada repository ini. Langkah-langkah berkontribusi pada repository ini:

1. Lakukan fork pada repository ini
2. Clone repository ke local
```bash
$ git clone git@github.com:<username>/PythonID.github.io.git
```
3. Masuk ke direktori repository
```bash
$ cd PythonID.github.io/
```
4. Buat branch baru selain master
```bash
$ git checkout -b nama-branch
```
5. Lakukan perubahan yang berkaitan dengan issue. Atau misal ingin menambahkan referensi belajar, bisa langsung ubah halaman `belajar.md`
6. Simpan perubahan
7. Lakukan commit dari perubahan yang telah dibuat dengan format
```bash
$ git commit -m "Pesan perubahan"
```
Atau jika berkaitan dengan Issue, sertakan dengan nomer issue

```bash
$ git commit -m "Berkaitan dengan #11 - Pesan perubahan"
```
8. Push perubahan ke remote repository dan buat branch baru pada remote repository
```bash
$ git push --set-upstream origin nama-branch
```
9. Lakukan pull request dengan melakukan klik pada link yang tersedia setelah berhasil push, atau buat [Pull Request](https://github.com/PythonID/PythonID.github.io/compare) secara manual pada github
10. Sertakan judul dan pesan pada pull request. Bila perlu gunakan format template yang sudah ada.
11. Menunggu hasil review
