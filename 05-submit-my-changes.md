Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu

Link Fork github
Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.

Link clone remote
Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.

git branch m-mfatriziagozali
Checkout ke dalam branch tersebut yang telah kamu buat

git checkout m-mfatriziagozali
Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md

touch mfatriziagozali.md
Isi file tersebut davidwinalda.md dengan konten di bawah ini:

Nama Lengkap: David Winalda Umur: 27 Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang

link pengisian dengan nano
Masukkan file .md tersebut ke dalam staging area

git add mfatriziagozali.md
Commit dengan memberikan pesan nama file .md kamu

git commit -m " add mfatriziagozali.md file"
git push origin m-mfatriziagozali ---> agar branch muncul di github sebelum di merge/di gabungkan dengan branch master
Merge branch yang telah kamu buat ke dalam branch master

git merge m-mfatriziagozali
Push ke dalam branch master

git push origin master
Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.

link full req
