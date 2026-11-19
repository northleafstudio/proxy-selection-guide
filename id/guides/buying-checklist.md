# Daftar singkat sebelum membeli paket proksi

Daftar ini diterbitkan oleh Northleaf Studio, yang juga mengoperasikan [ProxyVendors](https://proxyvendors.com/id/). Ini materi pendamping dari pihak yang sama, bukan rekomendasi pihak ketiga yang tidak terkait. Gunakan terhadap halaman harga yang berlaku, syarat, dan uji kecil. Daftar ini tidak menjamin bahwa suatu paket akan bekerja untuk target Anda.

## Bahasa

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- [日本語](../../ja/guides/buying-checklist.md)
- [Português](../../pt/guides/buying-checklist.md)
- [한국어](../../ko/guides/buying-checklist.md)
- [اردو](../../ur/guides/buying-checklist.md)
- **Bahasa Indonesia**
- [Türkçe](../../tr/guides/buying-checklist.md)
- [العربية](../../ar/guides/buying-checklist.md)
- [Polski](../../pl/guides/buying-checklist.md)
- [Italiano](../../it/guides/buying-checklist.md)
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- [Tiếng Việt](../../vi/guides/buying-checklist.md)
- [Русский](../../ru/guides/buying-checklist.md)

## 1. Tuliskan tugas, lalu pilih jaringan

Catat apa yang harus dilakukan keluar: masuk akun yang bertahan lama, data publik untuk wilayah tertentu, permintaan bervolume tinggi, atau uji operator seluler. Cocokkan itu dengan jenis jaringan, seperti pada [panduan jenis proksi](./proxy-types.md): residensial, pusat data, ISP, atau seluler. Jika beranda dan halaman harga mengiklankan harga awal atau jumlah negara yang berbeda, catat keduanya dan tanyakan angka mana yang berlaku untuk tingkat yang benar-benar akan dibeli.

## 2. Periksa perilaku sesi

Putuskan apakah keluar yang sama dibutuhkan selama menit, jam, atau seluruh masa sewa, atau keluar baru pada setiap permintaan. Pastikan lama lengket atau statis, apa yang memutuskannya, dan apakah IP yang putus diganti. Dokumentasi resmi kadang memberi dua lama penahanan; anggap hal itu belum selesai sampai penyedia mengonfirmasinya.

## 3. Pastikan protokol dan autentikasi

HTTP, termasuk [HTTP CONNECT](https://proxyvendors.com/id/glossary/http-connect) untuk situs HTTPS, tidak sama dengan [SOCKS5](https://proxyvendors.com/id/glossary/socks5). Sebagian produk residensial hanya mendukung HTTP dan HTTPS. Jika SOCKS5, atau UDP lewat SOCKS5, dibutuhkan, pastikan produk dan klien sama-sama mendukungnya. Pastikan host masuk, porta, dan metode autentikasi: nama pengguna dan kata sandi, daftar IP yang diizinkan, atau keduanya. Respons 407 selama CONNECT datang dari proksi. Status itu berarti Proxy Authentication Required: proksi meminta autentikasi, atau tidak menerima autentikasi yang diterimanya. Terowongan tidak terbentuk, dan situs target tidak pernah melihat permintaan itu.

## 4. Jumlahkan biaya yang nyata

Lihat lebih jauh dari harga satuan di judul. Catat pembelian minimum, masa berlaku atau kedaluwarsa paket, biaya kelebihan, trafik yang terbuang karena percobaan ulang, biaya tambahan penargetan halus, pajak, serta isi ulang atau perpanjangan otomatis. Harga yang ditonjolkan dapat milik tingkat volume besar, bukan paket yang akan dipakai untuk mulai. Jika uji meminta kartu dan mengaktifkan isi ulang otomatis, putuskan apakah fitur itu dimatikan sebelum uji dimulai.

## 5. Baca aturan uji, pengembalian dana, dan akses

Periksa ukuran dan lama uji, jendela pengembalian dana, batas pemakaian, dan apakah pengembalian dana mensyaratkan gangguan jaringan yang terdokumentasi. Perhatikan pemeriksaan identitas atau KYC, kategori yang diblokir seperti situs bank atau pemerintah, serta batas penggunaan wajar pada produk statis atau khusus. Jika asal atau kepatuhan penting, minta dokumentasi kepada penyedia, jangan hanya mengandalkan teks pemasaran.

## 6. Cari jaringannya, lalu uji

Jika operator tertentu dibutuhkan, pastikan [penargetan ASN](https://proxyvendors.com/id/glossary/asn) didukung dan apa yang terjadi ketika tidak ada keluar yang tersedia. Kemudian jalankan tugas nyata yang kecil: respons yang sah dari target, putusnya sesi, ketepatan lokasi, dan trafik yang benar-benar terpakai. Setelah terhubung, gunakan [pemeriksaan IP](https://proxyvendors.com/id/ip-check) untuk membandingkan IP publik, organisasi, dan ASN dengan produk yang dibeli, lalu jalankan pemeriksaan DNS dan WebRTC jika jalur itu penting.

Baru setelah itu putuskan berapa banyak yang dibeli.

— Northleaf Studio
