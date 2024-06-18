# Panduan Perintah Git

Panduan ini menyediakan referensi cepat untuk perintah-perintah Git umum yang akan Anda gunakan selama pengembangan.

## Konfigurasi

Atur konfigurasi username/email global Anda:

\`\`\`
git config --global user.name "Nama Anda"
git config --global user.email "email_anda@example.com"
\`\`\`

## Pengaturan Repositori

Inisialisasi repositori Git baru:

\`\`\`
git init
\`\`\`

## Commit Perubahan

Commit perubahan Anda dengan pesan deskriptif:

\`\`\`
git commit -m "Pesan commit Anda"
\`\`\`

## Melihat Riwayat

Lihat riwayat commit Anda:

\`\`\`
git log
\`\`\`

Untuk file tertentu atau entri terbatas, gunakan:

\`\`\`
git log -- [nama-file]
git log -[jumlah]
\`\`\`

## Branching

Daftar, buat, atau hapus branch:

\`\`\`
git branch
git branch [nama-branch-baru]
git branch -d [nama-branch]
\`\`\`

Berpindah antar branch:

\`\`\`
git checkout [nama-branch]
\`\`\`

Menggabungkan branch:

\`\`\`
git merge [nama-branch]
\`\`\`

## Repositori Remote

Kelola repositori remote Anda:

\`\`\`
git remote
git remote add [nama] [url]
\`\`\`

Push atau pull perubahan:

\`\`\`
git push [nama-remote] [nama-branch]
git pull
\`\`\`

Untuk perintah yang lebih detail dan strategi branching, silakan merujuk ke dokumentasi resmi Git.
