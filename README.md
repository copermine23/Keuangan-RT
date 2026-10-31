# Keuangan RT Android v1.2

Aplikasi Android WebView berdasarkan workbook `Aplikasi_Pembukuan_Keuangan_RT_Saldo_Per_Kategori.xlsx`.

## Fitur
- Dashboard saldo kas, pemasukan, pengeluaran, jumlah KK aktif, dan transaksi terbaru.
- Saldo setiap kategori pemasukan: Iuran Warga, Sumbangan, Bantuan Pemerintah, Hasil Kegiatan, Lain-lain, dan Arisan Ngaji.
- Saat mencatat pengeluaran, wajib memilih sumber dana kategori pemasukan. Nilai pengeluaran otomatis mengurangi saldo kategori sumber tersebut.
- Data warga/KK, iuran bulanan, cicilan iuran, status lunas/sebagian/belum bayar.
- Laporan bulanan, rekap pengeluaran menurut kategori dan sumber dana, kuitansi, ekspor CSV.
- Backup dan pemulihan data JSON.

## Cara menggunakan langsung di HP
Buka file `Keuangan_RT_Aplikasi_HP.html` dengan Chrome di Android. Untuk penggunaan lebih nyaman seperti aplikasi, gunakan paket Android di bawah. Data tersimpan lokal di perangkat/browser yang digunakan; lakukan backup secara berkala.

## Membuat APK Android
APK belum dikompilasi di paket ini. Untuk membuat APK debug:
1. Ekstrak ZIP proyek.
2. Buat repository baru di GitHub, lalu unggah seluruh isi folder proyek termasuk folder tersembunyi `.github`.
3. Buka tab **Actions**, pilih workflow **Build APK**, lalu tekan **Run workflow**.
4. Setelah proses berhasil, unduh artifact **Keuangan-RT-APK-v1.2**.
5. Ekstrak artifact dan instal `app-debug.apk` pada HP Android. Jika diminta, izinkan instalasi aplikasi dari sumber tersebut.

APK debug ditujukan untuk pemakaian pribadi/ujicoba. Data aplikasi disimpan lokal dan tidak otomatis tersinkron antar-HP.
