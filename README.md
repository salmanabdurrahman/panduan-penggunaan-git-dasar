# Dasar-Dasar Penggunaan Git untuk Pemula

Berikut adalah beberapa perintah dasar Git yang berguna untuk pemula:

1. **`ls`**: Menampilkan daftar isi direktori.

2. **Konfigurasi Global**:
   - `git config --global user.name "Nama Anda"`: Mengatur nama Anda untuk semua repositori di sistem Anda.
   - `git config --global user.email "email_anda@example.com"`: Mengatur email Anda untuk semua repositori di sistem Anda.

3. **`git init`**: Menginisialisasi repositori Git baru.

4. **Commit Perubahan**:
   - `git commit -m "Initial commit"`: Commit perubahan dengan pesan.

5. **Melihat Riwayat Commit**:
   - `git log`: Menampilkan log commit.
   - `git log -3`: Menampilkan 3 commit terakhir.
   - `git log -- style.css`: Menampilkan commit yang termasuk perubahan pada `style.css`.

6. **Checkout File**:
   - `git checkout [7-digit SHA] -- style.css`: Mengembalikan `style.css` ke keadaan pada commit tertentu.

7. **`git status`**: Memeriksa status perubahan sebagai untracked, modified, atau staged.

8. **Branching**:
   - `git branch`: Menampilkan daftar branch.
   - `git branch [nama-branch]`: Membuat branch baru.

9. **Visualisasi Branch**:
   - `git log --all --decorate --oneline --graph`: Menampilkan grafik ASCII dari riwayat branch.

10. **Membuat Alias**:
    - `alias graph="git log --all --decorate --oneline --graph"`: Membuat alias untuk perintah di atas.

11. **Berpindah Branch**:
    - `git checkout [nama-branch]`: Berpindah ke branch lain.

12. **Merging**:
    - Fast-forward merge: Penggabungan sederhana yang memindahkan pointer branch dasar ke depan.
    - Three-way merge: Penggabungan yang melibatkan nenek moyang bersama, membuat commit baru.

13. **Menggabungkan Branch**:
    - `git merge [nama-branch]`: Menggabungkan branch lain ke dalam branch saat ini.

14. **Menghapus Branch**:
    - `git branch -d [nama-branch]`: Menghapus branch yang telah digabungkan.
    - `git branch -D [nama-branch]`: Menghapus branch secara paksa tanpa digabungkan terlebih dahulu.

15. **Memeriksa Branch yang Telah Digabungkan**:
    - `git branch --merged`: Menampilkan daftar branch yang telah digabungkan ke dalam branch saat ini.

16. **Clone Repositori**:
    - `git clone [URL]`: Mengkloning repositori dari URL.

17. **Repositori Remote**:
    - `git remote`: Menampilkan koneksi remote.
    - `git remote add [nama] [url]`: Menambahkan koneksi remote baru dengan URL.

18. **Push Perubahan**:
    - `git push -u origin main`: Push perubahan ke branch utama dari repositori remote dan mengatur pelacakan upstream.

19. **Fetch Perubahan**:
    - `git fetch`: Mengambil perubahan dari repositori remote untuk memperbarui referensi lokal.

20. **Pull Perubahan**:
    - `git pull`: Mengambil dan menggabungkan perubahan dari repositori remote ke direktori kerja Anda.

Semoga rangkuman ini membantu Anda memahami dasar-dasar Git! Jika Anda memiliki pertanyaan lebih lanjut, jangan ragu untuk bertanya. 😊
