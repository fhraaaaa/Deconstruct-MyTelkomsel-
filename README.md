# Deconstruct: MyTelkomsel📶

**Versi** 1.0 • **Tanggal:** 2026-01-09
---

**Anggota Kelompok**
* **Ahmad Syehi Budin (1)**
* **Almira Meyta Anisa Kirana (3)**
* **Arwa Nicky Fahra Nabbiya (10)**
* **Inez Ayu Agustin (16)**
---
## 1. Ringkasan
MyTelkomsel merupakan sebuah aplikasi resmi dari Telkomsel yang sering digunakan pelanggan prabayar (sistem bayar di muka) dan pascabayar (bayar di akhir) untuk mengelola layanan telekomunikasi. MyTelkomsel menyedia berbagaikan pelayanan seperti manajemen akun (cek pulsa/kuota/poin), pembelian paket & isi ulang internet, pembayaran tagihan (PLN, BPJS, dll), hiburan (streaming video/musik/game), hingga fitur gaya hidup seperti belanja tiket pesawat/hotel dan layanan kesehatan.

---
## 2. Tujuan
* Memahami alur pengalaman pengguna (onboarding - penggunaan rutin - transaksi - layanan pelanggan).
* Mengidentifikasi fitur fitur dalam MyTelkomsel dan pola UI/UX dari MyTelkomsel.
* Menjadi refeerensi dalam membangun aplikasi digital layanan berbasis akun dan transaksi.

---
## 3. Target Pengguna & Persona
## A. Pengguna Prabayar 
   => Pengguna dengan sistem pembayaran **isi pulsa terlebih dahulu** sebelum layanan digunakan.
* **Fitur & Kebutuhan:**
- Cek sisa kuota internet, pulsa, dan masa aktif
- Isi pulsa dan pembelian paket data/telepon/SMS
- Akses cepat untuk kebutuhan harian
* **Tujuan:** Menjaga layanan tetap aktif dan memastikan kuota selalu tersedia.

## B. Pengguna Aktif (Power User)
   => Pengguna dengan intensitas penggunaan tinggi dan memanfaatkan fitur lanjutan.
* **Fitur & Kebutuhan:**
- Promo personal berdasarkan pola penggunaan
- Reward, poin loyalitas, dan penukaran hadiah
- Manajemen multi-nomor (keluarga / bisnis)
* **Tujuan:** Mendapatkan manfaat maksimal dari promo, reward, dan efisiensi layanan.

## C. Pengguna Pascabayar
   => Pengguna dengan sistem pembayaran **tagihan bulanan di akhir periode**.
* **Fitur & Kebutuhan:**
- Cek detail tagihan bulanan
- Pembayaran tagihan online
- Monitoring pemakaian kuota, telepon, dan SMS
* **Tujuan:** Mengontrol biaya dan memastikan pembayaran tepat waktu tanpa gangguan layanan.

---
## 4. Fitur Inti & Prioritas Produk
- **Account & Authentication**  
  Fitur login menggunakan nomor, verifikasi OTP, serta manajemen multi-nomor dalam satu akun pengguna.
- **Usage Monitoring**  
  Menyediakan informasi real-time terkait kuota internet, pulsa, dan masa aktif.
- **Paket & Add-ons**  
  Pembelian paket internet, telepon, SMS, dan roaming sesuai kebutuhan pengguna.
- **Checkout & Payments**  
  Sistem pembayaran fleksibel melalui pulsa, e-wallet, kartu pembayaran, dan pascabayar.
- **Rewards & Loyalty**  
  Program loyalitas berbasis poin (Telkomsel POIN), voucher, dan penukaran hadiah.
- **Customer Support**  
  Layanan bantuan melalui chatbot, live agent, dan help center.
- **Personalization**  
  Rekomendasi paket dan promo yang dipersonalisasi berdasarkan perilaku dan histori pengguna.

---
## 5.UI/UX Patterns
<p align="center">
  <img src="https://github.com/user-attachments/assets/51d8f7da-d06e-4002-8f65-cadb6d54fcfd" width="100" />
  <img src="https://github.com/user-attachments/assets/20dceeee-717e-42ac-a507-477ba64cb2e1" width="100" />
  <img src="https://github.com/user-attachments/assets/060e12b8-1926-4021-baee-4b7762361fda" width="100" />
  <img src="https://github.com/user-attachments/assets/c8bd3d3b-de9d-44a9-bf14-20fdd19d8a3e" width="100" />
  <img src="https://github.com/user-attachments/assets/bad0f240-1087-4184-ae3f-50689bf0ab6b" width="100" />
</p>

---
## 6. Site Map
<p align="center">
   <img src="https://github.com/user-attachments/assets/aad8ab2e-9495-4e03-ba69-13a1d2364487" width="650" />
</p> 

---
## 7. User Flow Diagrams 
<p align="center">
   <img src="https://github.com/user-attachments/assets/61b9b941-d2de-42b9-8d64-a8bf4721daa7" width="650" />
</p> 

---
## 8. ERD 
<p align="center">
   <img src="https://github.com/user-attachments/assets/d164bc18-3731-420b-910c-5039f5c2e06f" width="650" />
</p> 

---
## 9. Monetisasi & Model Bisnis
## A. Model Bisnis myTelkomsel
 => MyTelkomsel menggunakan platform digital service model, di mana aplikasi berfungsi sebagai pusat layanan pelanggan Telkomsel untuk produk telekomunikasi dan layanan digital.
 
* **Peran utama aplikasi:**
- Media penjualan produk Telkomsel
- Layanan pelanggan (self-service)
- Platform distribusi layanan digital & partner

## B. Sumber Monetisasi myTelkomsel
* **a. Penjualan Paket Telekomunikasi (Core Revenue)**
- Paket data internet
- Paket telepon & SMS
- Paket combo (internet + telpon + SMS)
=>Sumber pendapatan utama Telkomsel

* **b. Layanan Digital & Value Added Service (VAS)**
- Langganan musik, video streaming, dan game
- Konten premium (nonton, hiburan, edukasi)
- Cloud storage & digital lifestyle service
=> Pendapatan dari subscription & pay-per-use

* **c. Kerja Sama dengan Partner (B2B & Revenue Sharing)**
- Promo e-commerce (Shopee, Tokopedia, dll)
- Brand partner (voucher, diskon, cashback)
- Sistem bagi hasil (revenue sharing)

* **d. Iklan & Promosi Digital**
- Penempatan banner promo di aplikasi
- Campaign produk Telkomsel & partner
- Personalized ads berbasis data pengguna
=> Monetisasi dari iklan tertarget

* **e. Fintech & Pembayaran Digital**
- Pembelian pulsa & paket via e-wallet/bank
- Kerja sama payment gateway
- Biaya transaksi & komisi

## C. Segmen Pengguna
- Pelanggan prabayar Telkomsel
- Pelanggan pascabayar (Halo)
- Pengguna layanan digital & lifestyle

## D. Value Proposition
- Akses layanan Telkomsel dalam satu aplikasi
- Praktis, cepat, dan personal
- Banyak promo & reward pelanggan

## E. Keunggulan Model Bisnis
- Basis pengguna besar (jutaan pelanggan)
- Ekosistem layanan digital terintegrasi
- Data pelanggan mendukung personalisasi penawaran

---
## 10. Competitive Advantages & Risks
## A. Competitive Advantages (Keunggulan Kompetitif)
* **a. Basis Pengguna yang Sangat Besar**
=> MyTelkomsel terhubung langsung dengan jutaan pelanggan Telkomsel di seluruh Indonesia, sehingga memiliki *market yang sudah terbentuk* tanpa perlu akuisisi pengguna besar-besaran.

* **b. Integrasi Langsung dengan Layanan Inti Telkomsel**
=> Aplikasi terhubung langsung dengan sistem pulsa, paket data, nomor, dan tagihan pelanggan, sehingga layanan real-time, transaksi lebih cepat dan aman serta sulit ditiru kompetitor non-operator.

* **c. Ekosistem Digital yang Lengkap**
=> MyTelkomsel tidak hanya menjual paket, tetapi juga hiburan (streaming, game), promo & reward, layanan digital partner ini meningkatkan *retensi pengguna*.

* **d. Personalisasi Berbasis Data Pengguna**
=> Dengan data perilaku pelanggan, myTelkomsel dapat memberikan rekomendasi paket sesuai kebutuhan, promo yang lebih relevan, penawaran yang tepat sasaran yang dapat meningkatkan konversi penjualan.

* **e. Brand Kuat & Kepercayaan Tinggi**
=> Telkomsel dikenal sebagai operator dengan jaringan luas, kualitas sinyal stabil dan reputasi kuat. Hal ini meningkatkan *trust pengguna terhadap aplikasi*.

## B. Risks (Risiko)
* **a. Persaingan Ketat Industri Telekomunikasi**
=> Kompetitor seperti operator lain menawarkan paket lebih murah dan promo agresif sehungga dapat risiko penurunan loyalitas pelanggan

* **b. Ketergantungan pada Infrastruktur Teknologi**
=> Gangguan sistem, server down, atau bug aplikasi dapat mengganggu transaksi, menurunkan kepuasan pengguna dan memicu keluhan massal.

* **c. Risiko Keamanan Data & Privasi**
=> Aplikasi mengelola data sensitif pengguna (nomor, transaksi, kebiasaan digital), sehingga rentan terhadap serangan siber dan membutuhkan sistem keamanan tingkat tinggi.

* **d. Perubahan Regulasi Pemerintah**
=> Aturan terkait telekomunikasi, perlindungan data dan pajak layanan digital dapat memengaruhi operasional dan monetisasi aplikasi.

* **e. Ketergantungan pada Jaringan Telkomsel**
=> Kualitas aplikasi sangat bergantung pada kestabilan jaringan, kualitas layanan Telkomsel dan jika jaringan bermasalah, citra aplikasi ikut terdampak.

---
