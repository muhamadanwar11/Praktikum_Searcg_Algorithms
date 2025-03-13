# Depth First Search (DFS) in Python

## Deskripsi
Program ini mengimplementasikan algoritma **Depth First Search (DFS)** menggunakan bahasa pemrograman Python. DFS digunakan untuk menelusuri atau mencari node dalam graf menggunakan metode rekursif.

## Fitur
- Mewakili graf berarah menggunakan **daftar kejadian**.
- Menambahkan edge (sisi) ke dalam graf.
- Melakukan penelusuran DFS secara rekursif.
- Mencetak urutan node yang dikunjungi selama penelusuran DFS.

## Prasyarat
Pastikan Python telah terinstal di sistem Anda. Program ini menggunakan **Python 3**.

## Cara Menjalankan
1. Simpan file Python dengan nama `dfs.py`.
2. Jalankan program menggunakan terminal atau command prompt:
   ```sh
   python dfs.py
   ```
3. Output akan menampilkan hasil penelusuran DFS dari graf yang telah dibuat.

## Contoh Output
```
Berikut adalah Penelusuran Depth First (dimulai dari node 2):
2 0 1 3
```

## Struktur Kode
- **Graph Class**: Merepresentasikan graf berarah dan menyediakan metode untuk menambahkan edge serta melakukan DFS.
- **DFSUtil()**: Fungsi rekursif yang digunakan oleh DFS untuk menelusuri node.
- **DFS()**: Fungsi utama yang memulai DFS dari node tertentu.
- **Main Program**: Contoh penggunaan kelas `Graph` untuk membuat graf dan menjalankan DFS.

## Kontributor
Kode ini disumbangkan oleh **Neelam Yadav** dan telah diperbaiki serta disusun ulang untuk kejelasan lebih lanjut.

## Lisensi
Proyek ini bersifat open-source dan dapat digunakan untuk keperluan pendidikan dan pengembangan lebih lanjut.
