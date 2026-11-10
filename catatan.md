Catatan Pemahaman Git

Nama: M.Fariduddin
Nim : 2026583050005


1. Apa beda kondisi file modified, staged, dan committed?

	Modified adalah kondisi ketika file sudah diubah, tetapi perubahan belum dimasukkan ke staging.

	Staged adalah kondisi ketika perubahan sudah dipilih menggunakan git add dan siap untuk di-commit.

	Committed adalah kondisi ketika perubahan sudah disimpan ke dalam riwayat Git menggunakan git commit.


2. Mengapa developer tidak langsung mengubah main?

	Karena branch main merupakan branch utama proyek. Developer sebaiknya bekerja di branch masing-masing agar perubahan bisa diperiksa terlebih dahulu sebelum digabungkan ke main. Cara ini juga mengurangi risiko kesalahan pada proyek utama.


3. Apa beda git commit dan git push?

	git commit digunakan untuk menyimpan perubahan ke riwayat Git di komputer lokal.

	git push digunakan untuk mengirim commit dari komputer lokal ke repository GitHub.


4. Mengapa konflik terjadi pada slogan, tetapi tidak saat fitur kontak dan galeri digabung?

	Konflik terjadi pada slogan karena dua anggota mengubah bagian atau baris yang sama dalam file yang sama. Sementara itu, fitur kontak dan galeri dikerjakan pada bagian atau file yang berbeda sehingga tidak terjadi benturan perubahan.


5. Kapan memakai --amend dan kapan memakai revert?

	git commit --amend digunakan untuk memperbaiki atau mengganti commit terakhir yang belum dibagikan ke GitHub, misalnya memperbaiki pesan commit yang salah.

	git revert digunakan untuk membatalkan perubahan dari commit yang sudah dibuat, terutama jika sudah dibagikan ke GitHub. Perintah ini membuat commit baru sehingga riwayat sebelumnya tetap ada.