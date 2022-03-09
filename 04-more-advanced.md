1. What is the difference between git reset and git revert. When would you use one over the other?
2. What is the difference between git merge and git rebase. When would you use one over the other?
3. What is the difference between git stash pop and git stash apply. When would you use one over the other?
4. What kinds of things can you do in interactive mode when rebasing?

JAWAB :
1. -Git riset  = Untuk mengembalikan file ke kondisi sebelumnya dan menghapus commit berikutnya yang sudah dilakukan.
   -Git revert = Untuk kembali ke file sebelumnya, namun tidak menghapus sejarah commit yang sudah dilakukan.
2. -Git merge  = Bertujuan untuk menyatukan 2 atau lebih branch commit dengan syarat membuat branch baru tanpa mengedit langsung di branch utama.
   -Git rebase = Bertujuan untuk memindahkan branch dari lokasi satu ke lokasi lainnya.
3. -git stash pop   = Membuang simpanan yang berada pada posisi paling atas. 
   -git stash apply = Menyimpan data di daftar simpanan dan akan digunakan kembali.
4.  Rebasing interaktif => Digunakan untuk mengubah, mengedit, menghapus data dengan menggunakan commit. Gunakan SHA-1 dengan menggunakan commit untuk mengaktifkan interaktif pada rebase.
