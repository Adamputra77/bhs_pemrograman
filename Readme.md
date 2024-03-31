GITHUB COMMAND LINE..
git init : Perintah ini digunakan untuk membuat repository Git baru atau menginisialisasi repository Git yang sudah ada di direktori saat ini. Ini menciptakan struktur awal yang diperlukan oleh Git untuk melacak perubahan dan versi dari file dalam proyek.

git add adalah : Perintah ini digunakan untuk menambahkan semua perubahan yang ada di direktori kerja (working directory) ke dalam staging area. Dengan menggunakan tanda titik (.), Anda memberitahu Git untuk menambahkan semua perubahan, baik itu penambahan, pengeditan, atau penghapusan file.

git commit -m "pesan komit" : Setelah Anda menambahkan perubahan ke staging area dengan git add, Anda dapat mengonfirmasi perubahan tersebut dengan melakukan commit. Perintah git commit digunakan untuk membuat snapshot dari perubahan yang ada di staging area dan menyimpannya ke dalam repository Git.

git branch -M main : Perintah ini digunakan untuk mengubah nama branch utama dari default master ke main. Ini adalah praktik terbaru yang disarankan oleh komunitas Git untuk menghindari istilah yang tidak inklusif seperti master.
git remote add origin [link kode ssh di repository GitHub] : Perintah ini digunakan untuk menambahkan remote repository ke lokal repository Git Anda. origin adalah alias yang biasanya digunakan untuk merujuk ke remote repository utama. Link kode SSH digunakan untuk mengidentifikasi lokasi remote repository, sehingga Anda dapat melakukan operasi seperti push dan pull ke dan dari repository tersebut.

git push origin -u main : Perintah ini digunakan untuk mengirimkan perubahan dari branch lokal ke branch main di remote repository yang sudah ditetapkan sebelumnya sebagai origin. Opsi -u digunakan untuk mengatur branch lokal yang di-push agar secara otomatis terhubung dengan branch yang sesuai di remote repository. Ini memungkinkan Anda untuk menggunakan git push atau git pull tanpa menyertakan argumen tambahan seperti nama branch dan nama remote repository.

GITHUB COMMAND LINE SAAT MONITORING PROJECT (TAMBAH KURANG ISI FILE)
git add .
git commit -m "pesannya"
git push