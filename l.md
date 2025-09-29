# Unix Info
## Sejarah
- Pengembangan dimulai pada 1969.
- Pertama kali dibuat oleh Ken Thomson dan Dennis Ritchie (di Bell Labs, *research center* milik perusahaan AT&T).
- Awalnya, hanya bisa digunakan pada komputer Bell System. Namun, pada tahun 1970 lisensi Unix mulai dijual ke pihak lain, sehingga varian (distribusi) Unix dari perusahaan lain mulai dikembangkan juga.
- Unix terinspirasi oleh OS Multics.
    - Pembuat Unix merasa bahwa Multics punya tujuan yang baik, tetapi terlalu kompleks.
    - Jadi, mereka mencoba membuat OS sendiri yang lebih sederhana (hanya memiliki fitur penting aja).
- Saat dibuat, Unix menggunakan bahasa Assembly.
- Pada tahun 1973, versi 4 dibuat, yang menggunakan bahasa C.
    - Menggunakan bahasa C membuat Unix lebih mudah di-*port* ke sistem lain.
    - Cari definisi *port* di kamus.
- Versi Unix terakhir (yang dibuat oleh Bell Labs) adalah versi 10.
    - Namun, versi terakhir yang “terkenal” adalah versi 7, karena versi 8–10 tidak disebarluaskan.
- Unix menjadi inspirasi untuk banyak OS lain.

## Kebutuhan Hardware
**Khusus untuk Unix versi 7.**
>“Mengapa versi 7?”
>
>—Seseorang yang namanya tidak perlu disebutkan

Unix versi 7 adalah versi terakhir yang dibuat oleh Bell Labs yang terkenal. **Distribusi/versi Unix lain, yang mungkin juga dibuat oleh perusahaan lain, akan memiliki kebutuhan hardware yang berbeda.**

CPU    | RAM    | Penyimpanan
------ | ------ | -----------
PDP-11 | 256 KB | 2,5 MB

## Kelebihan dan Kekurangan

Kelebihan | Kekurangan
--------- | ----------
Stabil, jarang crash. Karena ini Unix sering dipakai pada server, yang hampir tidak pernah dimatikan. | Tidak memiliki GUI. Interaksi dengan komputer hanya menggunakan CLI (*Command-Line Interface*), sehingga lebih sulit digunakan, dan tidak enak dilihat (bagi orang awam).
Memiliki sistem file permission. | Lisensi restriktif. Pada zaman itu, lisensi harus dibeli. Namun sekarang, karena Unix sudah tidak dikembangkan, lisensinya gratis.
Multi-user, multi-tasking. Versi awal tidak memiliki fitur ini, tetapi versi lebih baru sudah ada. | Tidak *user-friendly*. Seperti yang sudah dijelaskan diatas. Unix juga memang dibuat untuk *programmer*, bukan pengguna umum.
Distribusi beragam. Karena lisensi Unix dijual, banyak perusahaan lain membuat versi Unix-nya sendiri dan mengembangkan fitur-fitur unik. | 
Kompatibilitas. Karena versi ke-4 menggunakan bahasa C, Unix menjadi lebih mudah untuk di-*port* ke sistem lain (dibandingkan sistem operasi lainnya pada saat itu, yang biasanya menggunakan bahasa Assembly). |





