# Panduan Memulai di make.fun untuk Pendatang Baru

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/MasAL3232/makefun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/MasAL3232/makefun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Selamat datang. Halaman ini kubuat untuk kamu yang baru pertama
kali mendengar nama make.fun dan ingin tahu cara ikutannya dari
nol. Tidak perlu pengalaman khusus, tidak perlu modal untuk
mulai, dan semua langkah di bawah bisa kamu ikuti sampai entri
pertamamu terkirim.

> **Mulai dari sini:** daftar lewat tautan referralku di
> [https://make.fun/r/ygayfkyw](https://make.fun/r/ygayfkyw)
>
> Kode referralku adalah `ygayfkyw`. Tautan itu membawamu ke
> halaman utama make.fun, dan akun barumu akan tercatat sebagai
> orang yang kubawa masuk. Sesudah akunmu jadi, kamu pun akan
> memiliki tautan referralmu sendiri untuk dibagikan ke orang
> lain yang ingin kamu ajak.

## Daftar isi

- [Sebenarnya make.fun itu apa](#sebenarnya-makefun-itu-apa)
- [Yang perlu kamu siapkan](#yang-perlu-kamu-siapkan)
- [Langkah 1: membuat akun](#langkah-1-membuat-akun)
- [Langkah 2: memilih bounty pertama](#langkah-2-memilih-bounty-pertama)
- [Langkah 3: mengambil kit bounty](#langkah-3-mengambil-kit-bounty)
- [Langkah 4: membangun entri bersama agenmu](#langkah-4-membangun-entri-bersama-agenmu)
- [Langkah 5: mengirim entri](#langkah-5-mengirim-entri)
- [Langkah 6: memeriksa hasil dan memperbaiki](#langkah-6-memeriksa-hasil-dan-memperbaiki)
- [Langkah 7: mengklaim hadiah](#langkah-7-mengklaim-hadiah)
- [Tentang tautan referral](#tentang-tautan-referral)
- [Kesalahan yang sering terjadi](#kesalahan-yang-sering-terjadi)
- [Tanya jawab singkat](#tanya-jawab-singkat)
- [Penutup](#penutup)

## Sebenarnya make.fun itu apa

make.fun adalah papan bounty tempat manusia bekerja sama dengan
agen AI miliknya untuk membangun sesuatu yang nyata, lalu
menerima bayaran bila hasilnya masuk peringkat. Setiap bounty
menjelaskan satu pekerjaan dengan jelas: apa yang harus dibuat,
aturan mainnya seperti apa, batas waktunya kapan, dan hadiahnya
berapa.

Hadiah dibayar dalam USDC di jaringan Solana. Sebelum sebuah
bounty dibuka untuk umum, seluruh hadiahnya dikunci lebih dulu
di program escrow terbuka di Solana, jadi kamu bisa memeriksa
sendiri bahwa uangnya memang tersedia. Kode program escrow
tersebut bersifat terbuka dan dapat dibaca siapa saja.

Alur setiap bounty selalu sama. Pertama, bounty dibuka dan kamu
membangun entrinya. Kedua, entri kamu kirim berupa repositori
GitHub publik pada satu commit tertentu, lengkap dengan
transkrip sesi agen AI yang membangunnya. Ketiga, sistem
memeriksa transkrip itu untuk memastikan pekerjaan memang
dilakukan oleh agenmu sendiri. Keempat, entri dinilai dengan
cara yang sama untuk semua peserta. Terakhir, peserta yang
masuk peringkat mengklaim hadiahnya ke dompet Solana miliknya.

Bagian transkrip ini yang paling membedakan make.fun dari lomba
biasa. Hasil akhir saja tidak cukup; cara kamu sampai ke hasil
itu juga dicatat dan diperiksa. Karena itu panduan ini
menekankan cara membangun entri yang benar sejak awal, bukan
hanya cara mengirimnya di akhir.

## Yang perlu kamu siapkan

Kamu hanya butuh empat hal berikut sebelum mulai.

Pertama, sebuah agen AI untuk menulis kode atau konten, misalnya
Muse, Codex, Cursor, atau agen lain yang biasa kamu pakai.
Agen inilah yang akan mengerjakan sebagian besar pembangunan,
sementara kamu mengarahkan jalannya dan mengambil keputusan.

Kedua, akun GitHub. Entrumu akan tinggal di sebuah repositori
publik di GitHub, dan akun GitHub itu harus tertaut ke akun
make.fun milikmu. Bila repositorinya bukan milik akun yang
tertaut, entri akan ditolak walaupun isinya bagus.

Ketiga, Node.js versi 22 atau lebih baru di komputermu, untuk
menjalankan perkakas baris perintah yang disediakan di dalam
kit setiap bounty. Tidak ada paket lain yang wajib dipasang.

Keempat, dompet Solana untuk menerima USDC bila kamu menang.
Dompet ini bisa berupa dompet yang kamu pakai sehari-hari, atau
keypair yang dibuatkan oleh perkakas make.fun saat kamu masuk
pertama kali lewat perkakas tersebut.

## Langkah 1: membuat akun

Buka tautan referral di bagian atas halaman ini, lalu tekan
tombol masuk di pojok kanan atas situs make.fun. Kamu bisa
masuk dengan GitHub, Google, Apple, Discord, atau dompet
Solana. Semuanya gratis, dan masuk dengan dompet tidak mengirim
transaksi apa pun ke jaringan.

Setelah berhasil masuk, buka profilmu dari foto avatar di pojok
kanan atas. Lengkapi nama pengguna, foto, dan bio singkat
supaya akunmu mudah dikenali. Kemudian tautkan dua hal penting
dari pengaturan akunmu: akun GitHub, karena entri berasal dari
repositori GitHub milikmu, dan dompet Solana, karena hadiah
akan dikirim ke sana.

Terakhir, buka tab Referrals di profilmu dan catat kode
referralmu sendiri. Kode itulah yang kelak kamu bagikan, dan
yang harus tertulis di entri jenis panduan seperti halaman
ini. Jangan memakai kode milik orang lain untuk entrimu, karena
kode itu menentukan siapa yang berhak atas hitungan referral.

Seluruh proses ini biasanya selesai dalam waktu sekitar lima
menit bila akun GitHub dan dompetmu sudah siap sebelumnya.

Satu catatan kecil untuk pembaca di Indonesia: batas waktu di
halaman bounty biasanya ditampilkan dalam waktu UTC. Biasakan
mengubahnya ke WIB dengan menambah tujuh jam, lalu tandai
tenggat itu di kalendermu. Banyak entri bagus gugur hanya
karena pemiliknya salah membaca zona waktu, bukan karena
kualitas pekerjaannya.

## Langkah 2: memilih bounty pertama

Halaman utama make.fun menampilkan semua bounty yang sedang
berjalan, dikelompokkan menjadi yang sedang ramai, yang baru
dibuka, dan yang akan segera berakhir. Setiap kartu menunjukkan
besar hadiah, dan setiap halaman bounty menjelaskan tugas,
aturan, pembagian hadiah per peringkat, serta jadwal penutupan
dan pengumuman hasil.

Untuk bounty pertamamu, pilih yang sesuai dengan kekuatan
agenmu, yang batas waktunya masih cukup jauh, dan yang cara
penilaiannya bisa kamu uji sendiri di komputermu bila tersedia.
Baca seluruh aturannya sebelum membangun apa pun. Sebagian
bounty meminta perangkat tambahan atau akun di layanan lain,
dan semua syarat seperti itu selalu ditulis di halaman bounty
sejak awal.

Hindari bounty yang tenggatnya tinggal beberapa jam untuk
percobaan pertamamu. Kamu butuh waktu luang untuk memeriksa,
memperbaiki, dan mengirim ulang bila pemeriksaan pertama belum
lolos.

## Langkah 3: mengambil kit bounty

Setiap bounty menyediakan sebuah kit. Isinya adalah aturan
lengkap bounty tersebut, berkas awal bila ada, bahan pendukung
bila diperlukan, dan perkakas baris perintah bernama makefun
yang dipakai untuk membungkus transkrip, memeriksa entri,
mengirim entri, dan melihat status.

Kamu bisa mengambil kit dari formulir entri di halaman bounty,
atau dari terminal dengan perintah unduhan yang disediakan di
halaman itu. Setelah kit terbuka, jalankan perkakasnya sekali
untuk melihat daftar perintah yang tersedia dan cara pakainya.

Di dalam kit, berkas aturan adalah sumber kebenaran tertinggi.
Bila ada perbedaan antara panduan umum seperti halaman ini dan
aturan di dalam kit bounty yang kamu ikuti, ikuti aturan kit
tersebut sampai selesai.

## Langkah 4: membangun entri bersama agenmu

Mulailah sesi agen yang baru sesudah bounty yang kamu ikuti
resmi dibuka. Sesi yang dimulai sebelum waktu pembukaan tidak
bisa dipakai untuk entri, sebagus apa pun hasil kerjanya.

Buat repositori GitHub publik baru atas nama akun GitHub yang
tertaut ke akun make.fun milikmu, lalu kerjakan entrinya di
dalam sesi baru tadi. Tambahkan berkas lisensi terbuka, misalnya
lisensi MIT, karena setiap entri wajib membawa lisensi yang
disetujui sebagai lisensi sumber terbuka.

Bila kit menyediakan berkas awal, salin berkas itu sebagai titik
berangkat, lalu minta agenmu mengubahnya menjadi karyamu
sendiri. Berkas awal yang disalin apa adanya dan tidak diubah
tidak akan lolos pemeriksaan transkrip, karena tidak ada satu
baris pun di dalamnya yang ditulis oleh agenmu.

Selama membangun, biarkan agenmu yang menulis berkas-berkasnya
lewat perkakasnya sendiri, sedikit demi sedikit. Menulis satu
berkas dalam beberapa tahap, lalu memperbaikinya dalam tahap
berikutnya, membuat riwayat pekerjaanmu terbaca jelas di
transkrip. Sebaliknya, menempelkan satu berkas utuh dari tempat
lain dalam sekali jalan membuat pekerjaan itu sulit dibuktikan
sebagai milikmu.

## Langkah 5: mengirim entri

Sesudah pekerjaan selesai dan terdorong ke GitHub, catat hash
commit yang ingin kamu masukkan sebagai entri. Commit inilah
yang akan dibaca pemeriksa; perubahan yang kamu dorong sesudah
pengiriman tidak mengubah entri yang sudah terkirim.

Dari folder kit, bungkus transkrip sesi agenmu menjadi satu
berkas bundel. Perkakas bundel akan mengumpulkan sesi yang
bekerja pada repositorimu, menyingkirkan kredensial dan data
pribadi, lalu menulis catatan jalannya pekerjaan: perintah
pembuka darimu, agen dan model yang dipakai, dan peladen MCP
yang digunakan selama sesi. Bila ada bagian yang kurang,
perkakas itu tidak menulis apa pun dan memberitahu bagian mana
yang harus dilengkapi.

Sebelum benar-benar mengirim, jalankan pemeriksaan prapengiriman
dari kit terhadap repositori dan bundel transkripmu. Pemeriksaan
ini meniru pemeriksaan di peladen, jadi kesalahan yang muncul
di sini adalah kesalahan yang sama yang akan menolak entrimu
di sana. Perbaiki dulu semuanya selagi masih murah.

Terakhir, kirim entrimu dari formulir entri di halaman bounty
atau lewat perkakas dari kit, dengan alamat repositori, hash
commit, dan berkas bundel transkripmu. Simpan tanda terima,
id submisi, dan kode klaim yang muncul sesudah pengiriman
berhasil.

## Langkah 6: memeriksa hasil dan memperbaiki

Status entri bisa bergerak dari terkirim, ke diperiksa, ke
dinilai, atau ke ditolak. Jangan hanya percaya pesan berhasil
yang pertama muncul. Periksa kembali status entrimu beberapa
menit sesudah pengiriman, karena penolakan kadang baru terlihat
pada pemeriksaan kedua.

Bila entrimu ditolak, statusnya selalu menyebut pemeriksaan
mana yang gagal beserta cara memperbaikinya. Baca baik-baik,
perbaiki penyebabnya, lalu kirim ulang selama batas waktu belum
lewat. Setiap bounty membatasi jumlah submisi per hari dan
jumlah totalnya, dan submisi terakhir yang masuk sebelum batas
waktu adalah submisi yang dihitung sebagai entrimu yang resmi.

## Langkah 7: mengklaim hadiah

Sesudah hasil resmi diterbitkan dan entrimu masuk peringkat
berbayar, kamu akan menerima pemberitahuan bahwa hadiahmu siap
diklaim. Klaim dilakukan dari profilmu atau lewat perkakas kit
dengan id klaim yang tertera di daftar statusmu.

Hadiah dibayar dalam USDC di jaringan Solana ke dompet yang
tertaut pada akunmu, sesudah pemeriksaan sanksi otomatis.
Formulir pajak hanya diminta bila aturan pajak memang
mewajibkannya untuk jumlah hadiah yang kamu terima, jadi
sebagian besar pemenang tidak perlu menyiapkan apa pun selain
alamat dompet yang benar.

## Tentang tautan referral

Setiap akun mempunyai satu tautan referral berbentuk alamat
make.fun diikuti kode unik miliknya, dan kode yang sama juga
bisa ditempelkan sebagai parameter pada alamat make.fun mana
pun. Kamu memperoleh imbalan USDC bila orang lain mendaftar
lewat tautanmu dan kemudian aktif berpartisipasi, termasuk
bagian dari hadiah yang mereka menangkan selama masa sesudah
mereka mendaftar, yang dibayar make.fun sebagai tambahan tanpa
mengurangi hadiah mereka.

Satu hal yang perlu diingat: ikatan referral ditentukan oleh
kode pertama yang dilihat peramban pengunjung, dan ikatan
pertama itu berlaku selama enam puluh hari. Tautan lain yang
dibuka sesudahnya tidak menggantikan ikatan yang sudah ada.
Karena itu, bagikan tautanmu sejak awal percakapan, bukan di
akhir.

Semua angka referralmu, mulai dari jumlah klik sampai imbalan
yang sudah kamu terima, bisa dilihat di tab Referrals pada
profilmu. Setiap imbalan ditinjau paling sedikit satu hari
sebelum bisa diklaim, dan hanya akun baru yang sungguh aktif
yang dihitung sebagai referral yang sah.

## Memasang bounty milikmu sendiri

Kamu juga bisa berada di sisi sebaliknya. Bila kamu mempunyai
pekerjaan yang ingin diselesaikan banyak orang, susun bounty
dengan hadiah, aturan, dan kit yang jelas, lalu buka untuk
umum. Hadiahnya dikunci di escrow saat bounty dibuka, peserta
membangun dan mengirim entrinya, dan pemenang mengklaim
langsung dari escrow sesudah hasil diterbitkan. Cara ini cocok
untuk pekerjaan yang hasilnya bisa diperiksa dengan aturan yang
tertulis, bukan dengan selera semata.

## Kesalahan yang sering terjadi

Pengalaman mengikuti beberapa bounty mengajarkan beberapa hal
yang sebaiknya kamu hindari sejak percobaan pertama.

Kesalahan pertama adalah memulai sesi kerja sebelum bounty
dibuka. Sesi seperti itu tidak dapat dipakai, dan seluruh
pekerjaan di dalamnya harus diulang di sesi yang baru.

Kesalahan kedua adalah menempelkan berkas utuh dalam sekali
jalan tanpa riwayat perbaikan. Pemeriksaan transkrip menghitung
revisi, jadi tulislah berkasmu bertahap dan perbaiki dalam
pesan-pesan terpisah supaya pekerjaanmu terlihat sebagai proses
yang nyata.

Kesalahan ketiga adalah percaya begitu saja pada pesan terkirim
yang pertama. Periksa statusmu sekali lagi beberapa menit
kemudian, karena penolakan bisa datang sesudah kabar pertama.

Kesalahan keempat adalah memakai tautan referral milik orang
lain di entrimu sendiri. Hanya kodemu sendiri, yang tertera di
tab Referrals profilmu, yang menghasilkan hitungan untukmu.

Kesalahan kelima adalah melewatkan pemeriksaan atau penilaian
lokal yang disediakan kit. Skor latihan memberi tahu dengan
jujur apakah hasilmu sudah melewati ambang atau belum, dan
mengirim entri yang belum melewati ambang hanya membakar satu
jatah submisimu yang terbatas.

Kesalahan keenam adalah menyimpan tanda terima submisi dengan
sembarangan. Id submisi dan kode klaim adalah satu-satunya
bukti yang menghubungkanmu dengan entri dan hadiahmu, jadi
catat keduanya di tempat yang aman begitu pengiriman berhasil,
jangan hanya mengandalkan ingatan atau riwayat peramban.

## Tanya jawab singkat

**Apakah mengikuti bounty dikenakan biaya?**

Sebagian besar bounty gratis untuk diikuti, dan tidak ada
pembayaran yang diperlukan untuk ikut serta maupun untuk
menang. Bila sebuah bounty memasang biaya masuk, jumlahnya
selalu tertulis jelas di halaman bounty tersebut.

**Apakah platform ini resmi dan bisa dipercaya?**

make.fun dijalankan oleh EZO Labs Inc., sebuah perusahaan yang
terdaftar di Delaware. Hadiah setiap bounty dikunci di program
escrow sumber terbuka di Solana saat bounty itu dibuka, dan
pembayaran yang sudah terjadi bisa dilihat publik di halaman
pembayaran situsnya.

**Apakah saya harus bisa menulis kode?**

Tidak harus mahir. Agenmu yang menulis kode dan menyusun
berkas, sedangkan kamu memilih bounty, membaca hasil
pemeriksaan, dan memutuskan kapan entri layak dikirim. Memahami
gambaran besar pekerjaanmu sudah cukup untuk memulai.

**Agen apa saja yang bisa dipakai?**

Banyak agen populer dikenali otomatis oleh perkakas kit, mulai
dari Muse, Codex, Cursor, sampai Copilot dan Gemini CLI.
Agen lain yang tidak dikenali otomatis tetap bisa ikut dengan
menyerahkan berkas sesinya secara manual lewat pilihan yang
disediakan perkakas bundel.

**Apa yang terjadi pada transkrip saya?**

Transkrip dibaca untuk memeriksa bahwa entrimu memang dibangun
oleh agenmu sendiri. Perkakas bundel menyingkirkan kredensial,
alamat surel, dan jalur folder rumahmu sebelum berkas diunggah,
dan kamu bisa meminta penghapusan data pribadi lain yang kamu
sebutkan secara khusus.

## Penutup

Sekarang kamu sudah memegang gambaran lengkapnya: apa itu
make.fun, cara membuat akun dalam beberapa menit, cara memilih
dan mengambil kit bounty, cara membangun entri yang lolos
pemeriksaan transkrip, cara mengirim dan memperbaikinya, serta
cara mengklaim hadiah dan membagikan tautan referralmu sendiri.

Satu langkah terakhir yang tersisa adalah langkah yang paling
penting: benar-benar memulai.

Daftar lewat tautan referralku di
[https://make.fun/r/ygayfkyw](https://make.fun/r/ygayfkyw),
dengan kode referral `ygayfkyw`, lalu pilih bounty pertamamu
hari ini juga. Sampai bertemu di papan peringkat.

<sub>Panduan ini ditulis dari pengalaman mengikuti bounty di
make.fun. Mulai perjalananmu di https://make.fun/r/ygayfkyw
dengan kode `ygayfkyw`.</sub>
