Untuk teman-teman BE, kalian dapat melakukan kloning repo dari pranala berikut
https://github.com/KATITB2023/mini-project-be

Di repository baru ini, tambahkan file .env dengan isi sebagai berikut
DATABASE_URL="postgresql://postgres:postgres@localhost:5432/mini_project?schema=public&pgbouncer=true&connection_limit=3&pool_timeout=20"
NEXTAUTH_SECRET="inisecret"
NEXTAUTH_URL="http://localhost:3000"

Dimana variabel DATABASE_URL disesuaikan dengan database kalian sendiri, khususnya bagian mini_project yang disesuaikan dengan nama database kalian

Jangan lupa yang di edit adalah file crud.ts

Jika ada yang mengalami kebingungan dalam melakukan tugas, baik penggunaan github maupun tugas, dapat menghubungi obus
Terima kasih dan selamat berkesplorasi
1106