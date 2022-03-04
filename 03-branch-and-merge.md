What does git clean do?
Ini adalah perintah bawaan untuk membersihkan file yang tidak terlacak. Ini bisa termasuk menghapus artefak build sementara atau menggabungkan file konflik.

What do the -d and -f flags for git clean do?
Jika Anda juga ingin menghapus direktori, jalankan git clean -f -d

What git command creates a branch?
git branch <nama_branch>

What is the difference between a fast-forward and recursive merge?
Dalam strategi penggabungan yang paling umum digunakan ini, sejarah hanyalah satu garis lurus. Saat Anda membuat cabang, buat beberapa komit di cabang itu, saat Anda siap untuk menggabungkan, tidak ada penggabungan baru di master. Dengan begitu penunjuk master hanya bergerak lurus ke depan dan sejarah adalah satu garis lurus.
Dalam penggabungan Rekursif, setelah Anda bercabang dan membuat beberapa komit, ada beberapa komit asli baru di 'master'. Jadi, ketika saatnya untuk menggabungkan, git berulang di atas cabang dan membuat komit gabungan baru. Komit gabungan terus memiliki dua orang tua.

What git command changes to another branch?
git checkout <nama_branch>

How do you remove modified or deleted files from the working directory?
rm <nama_file>

What git command deletes a branch?
git branch -d <nama_branch>

What does the git diff command do?
Perintah git diff akan membandingkan perubahan yang baru saja dilakukan dengan revisi/commit terakhir pada repository.

How do you remove files from the staging area?
git reset HEAD <nama_file>

How do merge conflicts happen?
dengan menggabungkan branch master dengan branch lain yang sudah di edit isi nya sebelumnya agar tidak terjadi konflik.
