# Native Power App

## Deskripsi Aplikasi

Native Power App adalah aplikasi React Native berbasis Expo yang memungkinkan pengguna mengambil foto menggunakan kamera atau memilih foto dari galeri, kemudian menyimpan foto beserta koordinat lokasi GPS ke penyimpanan lokal menggunakan AsyncStorage.

Data yang telah disimpan akan tetap tersedia meskipun aplikasi ditutup dan dibuka kembali. Pengguna juga dapat membuka lokasi pada Google Maps serta menghapus data yang tersimpan.

---

## Native Features yang Digunakan

* 📷 Camera (expo-image-picker)
* 🖼️ Image Library / Gallery (expo-image-picker)
* 📍 GPS Location (expo-location)
* 💾 AsyncStorage (@react-native-async-storage/async-storage)
* 🔗 Deep Linking (Google Maps)
* 🔐 Permission Handling (Camera, Gallery, dan Location)

---

# Daftar Fitur

## Level 1

* ✅ Mengambil foto menggunakan kamera
* ✅ Memilih foto dari galeri
* ✅ Menampilkan hasil foto
* ✅ Meminta izin kamera
* ✅ Meminta izin galeri

## Level 2 ✅

* ✅ Mengambil koordinat GPS saat foto dipilih
* ✅ Menyimpan foto dan lokasi menggunakan AsyncStorage
* ✅ Data tetap tersimpan setelah aplikasi dibuka kembali
* ✅ Membuka lokasi di Google Maps
* ✅ Menampilkan dialog ketika izin ditolak
* ✅ Tombol Reset untuk menghapus seluruh data

---

# Screenshot

## 1. Hasil Foto dan Lokasi

> Tambahkan screenshot yang menampilkan foto serta koordinat GPS.

Contoh:

```
<a href="https://ibb.co.com/MxNqxQ29"><img src="https://i.ibb.co.com/MxNqxQ29/Whats-App-Image-2026-06-28-at-05-18-06.jpg" alt="Whats-App-Image-2026-06-28-at-05-18-06" border="0"></a>
```

---

## 2. Dialog Izin Kamera / Lokasi

> Tambahkan screenshot dialog permission.

Contoh:

```
<a href="https://ibb.co.com/hFZQrqTF"><img src="https://i.ibb.co.com/hFZQrqTF/Whats-App-Image-2026-06-28-at-05-18-05.jpg" alt="Whats-App-Image-2026-06-28-at-05-18-05" border="0"></a>
```

---

## 3. Penanganan Penolakan Izin

> Tambahkan screenshot Alert ketika pengguna menolak izin dan tombol **Buka Pengaturan**.

Contoh:

```
<a href="https://ibb.co.com/S7rQ4yND"><img src="https://i.ibb.co.com/S7rQ4yND/Whats-App-Image-2026-06-28-at-05-18-07.jpg" alt="Whats-App-Image-2026-06-28-at-05-18-07" border="0"></a>
```

---

# Cara Menjalankan

Clone repository

```bash
git clone <repository-url>
```

Masuk ke folder project

```bash
cd profile-card
```

Install dependency

```bash
npm install
```

Jalankan Expo

```bash
npx expo start
```

Scan QR Code menggunakan aplikasi Expo Go.

---

# Tech Stack

* React Native
* Expo SDK 54
* Expo Image Picker
* Expo Location
* AsyncStorage
* JavaScript

---

# Link Expo Snack

Tambahkan link Expo Snack di bawah ini.

```
https://snack.expo.dev/xxxxxxxx
```

---

# Author

Nama: DARMAN Michael
