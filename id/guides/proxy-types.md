# Jenis proksi: jaringan, penetapan, dan protokol

Panduan ini diterbitkan oleh Northleaf Studio, yang juga mengoperasikan [ProxyVendors](https://proxyvendors.com/id/), direktori untuk membandingkan penyedia menurut tugas, sesi, lokasi, dan biaya. Ini materi latar dari pihak yang sama, bukan ulasan independen atas situs itu atau penyedia mana pun oleh pihak ketiga yang tidak terkait. Label produk berubah, dan dua halaman resmi dari penyedia yang sama dapat berbeda. Gunakan teks ini sebagai peta istilah, lalu pastikan rinciannya pada dokumentasi penyedia yang berlaku.

## Bahasa

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- [Español](../../es/guides/proxy-types.md)
- [Deutsch](../../de/guides/proxy-types.md)
- [Français](../../fr/guides/proxy-types.md)
- [日本語](../../ja/guides/proxy-types.md)
- [Português](../../pt/guides/proxy-types.md)
- [한국어](../../ko/guides/proxy-types.md)
- [اردو](../../ur/guides/proxy-types.md)
- **Bahasa Indonesia**
- [Türkçe](../../tr/guides/proxy-types.md)
- [العربية](../../ar/guides/proxy-types.md)
- [Polski](../../pl/guides/proxy-types.md)
- [Italiano](../../it/guides/proxy-types.md)
- [ไทย](../../th/guides/proxy-types.md)
- [Українська](../../uk/guides/proxy-types.md)
- [Tiếng Việt](../../vi/guides/proxy-types.md)
- [Русский](../../ru/guides/proxy-types.md)

## Tiga pertanyaan yang berbeda

Orang sering menggabungkan tiga pertanyaan menjadi satu kata, “proksi”:

1. **Dari jaringan seperti apa IP keluar berasal?** Inilah arti biasa dari residensial, pusat data, ISP, dan seluler.
2. **Berapa lama keluar yang sama tetap ditetapkan?** Ini perbedaan statis dan berputar, kadang disebut sesi lengket.
3. **Bagaimana klien terhubung?** Ini HTTP, termasuk terowongan [HTTP CONNECT](https://proxyvendors.com/id/glossary/http-connect) untuk HTTPS, atau [SOCKS5](https://proxyvendors.com/id/glossary/socks5).

IP statis tetap dapat dipakai bersama pelanggan lain. Titik akhir SOCKS5 adalah metode koneksi, bukan jenis IP. Keluar residensial atau pusat data yang sama sering dapat dijangkau lewat lebih dari satu protokol, dan sebagian produk hanya mendukung HTTP atau HTTPS.

## Jenis jaringan

**Residensial.** Keluar terkait dengan jaringan konsumen atau pita lebar. Ini pilihan yang biasa ketika target peka terhadap rentang hosting, atau ketika lokasi perlu tampak seperti koneksi rumah biasa. Trafik residensial sering ditagih per gigabita. Pool bersifat bersama dan berputar, kecuali opsi lengket atau khusus dibeli. Label itu klasifikasi dari penyedia atau basis data pihak ketiga; itu bukan ruas yang dibawa oleh IP itu sendiri.

**Pusat data.** Keluar berasal dari jaringan hosting atau awan. Produk ini sering lebih murah per satuan trafik atau per IP, dan dapat memberi laju yang lebih tinggi untuk volume permintaan yang besar. Banyak situs memperlakukan rentang pusat data dengan lebih ketat. Sebelum membeli paket besar, periksa apakah target mengembalikan isi yang sah melalui jenis keluar itu.

**ISP, kadang dijual sebagai residensial statis.** Alamat biasanya terdaftar atas nama penyedia akses internet rumah, sedangkan host proksi sendiri sering berada di pusat data. ISP menamai pendaftaran itu; hal itu sendiri tidak berarti keluar tetap diam. Penjual sering memasangkan label ini dengan penetapan yang lebih lama, yang cocok untuk masuk akun, daftar IP yang diizinkan, dan lokasi tetap. Pastikan apakah IP khusus atau bersama, apa yang terjadi saat terputus atau diperpanjang, dan apakah ada pemeriksaan identitas.

**Seluler.** Keluar berasal dari jaringan operator seluler, biasanya 4G atau 5G. Ini dipakai untuk iklan seluler, halaman khusus operator, dan konten regional yang berbeda di jaringan seluler. Penagihan dapat per gigabita, per hari, atau per porta. Periksa stok operator dan negara, aturan rotasi, serta batas pemakaian, karena persediaan seluler sering lebih tipis daripada pool residensial.

Tidak satu pun label ini merupakan nilai mutu. Diterima atau tidaknya permintaan bergantung pada keluar, pola permintaan, dan kebijakan target sendiri.

## Penetapan: statis, berputar, dan lengket

Berputar biasanya berarti keluar baru dipilih pada setiap permintaan, atau pada selang yang pendek. Lengket atau statis biasanya berarti keluar yang sama dipertahankan selama sesi atau masa sewa. Penyedia tidak memakai kata-kata ini dengan cara yang sama, dan halaman resmi kadang memberi dua lama sesi. Jika tugas membutuhkan IP yang sama, dapatkan lama penahanan yang pasti, syarat yang memutuskannya, dan apakah IP pengganti dijamin.

## ASN bukan jenis keempat

[ASN](https://proxyvendors.com/id/glossary/asn) mengidentifikasi operator perutean yang mengumumkan blok alamat. ASN dapat lebih tepat daripada negara ketika jaringan satu operator dibutuhkan. ASN bukan negara, dan tidak memberitahu apakah IP itu residensial atau pusat data. Meminta satu ASN juga mengecilkan pool; jika tidak ada keluar yang tersedia, permintaan dapat gagal.

## Setelah memilih jenis, periksa keluar

Halaman paket menjelaskan produk yang hendak dibeli. [Pemeriksaan IP](https://proxyvendors.com/id/ip-check) menampilkan IP publik, organisasi, dan ASN yang benar-benar diterima, ditambah pemeriksaan DNS dan WebRTC yang opsional. Jika hasil itu tidak sesuai dengan produk yang dibeli, berhentilah dan selesaikan hal itu sebelum menaikkan volume.

Saat membandingkan paket tertentu, gunakan [daftar periksa pembelian](./buying-checklist.md).

— Northleaf Studio
