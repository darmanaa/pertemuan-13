# Native Power App (Profile-style)

A small Expo app demonstrating camera + location native features, permission flow, and persistence.

## Fitur
- Ambil foto via Kamera atau pilih dari Galeri (permission flow)
- Ambil koordinat lokasi saat foto diambil (GPS)
- Persistensi: foto + koordinat disimpan di AsyncStorage dan dimuat saat app dibuka
- Buka koordinat di Google Maps
- Tombol reset untuk menghapus data

Level 2: Camera + Location (digabung) dan Persistensi (AsyncStorage)

## Cara Menjalankan

1. Install dependencies:

```bash
npm install
```

2. Jalankan Expo:

```bash
npx expo start
```

3. Scan QR dengan Expo Go pada HP fisik.

Catatan: Pastikan mengizinkan akses Kamera, Galeri, dan Lokasi saat diminta.

## Test Case yang Disarankan
- Ambil foto lewat Kamera → lihat foto tampil + koordinat muncul
- Pilih foto dari Galeri → lihat foto tampil + koordinat muncul
- Tolak izin Kamera/Lokasi → harus muncul Alert dan tidak crash
- Tekan `Buka di Maps` untuk membuka lokasi di Google Maps

## Expo Snack
Tambahkan kode ini ke https://snack.expo.dev/ untuk demo cepat.

## Commit Guidelines
Gunakan Conventional Commits, contoh:

```
feat: add camera + location persistence
```

## Files
- `App.js` — implementasi utama
- `package.json` — dependencies (expo-image-picker, expo-location, async-storage)

## Next Steps / Bonus
- Tambahkan reverse geocoding atau integrasi API cuaca untuk nilai lebih.
