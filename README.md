# Soundmate

Efek suara untuk HP yang membuat bass lebih padat, vokal lebih bulat, dan suara lebih penuh saat headset atau speaker Bluetooth tersambung. Tanpa root.

Soundmate bukan produk Dolby dan tidak berafiliasi dengan Dolby. Dolby dan Dolby Atmos adalah merek dagang Dolby Laboratories.

## Fitur

- Aktif otomatis saat headset atau speaker Bluetooth tersambung, dan mati saat terputus.
- Speaker HP dan headset kabel tetap normal.
- Pengaturan tersimpan terpisah untuk tiap perangkat Bluetooth.
- Preset: Musik, Film, Game, Suara, Bass, dan Datar.
- Kustom 1 dan Kustom 2 untuk menyimpan pengaturan sendiri.
- Equalizer 10 pita, serta penggeser Penguat bass, Efek surround, Penjernih dialog, dan Penguat volume.
- Tidak meminta izin internet.

## Persyaratan

- Android 8.0 atau lebih baru. Efek paling lengkap ada di Android 9 atau lebih baru.
- Headset atau speaker Bluetooth.

## Cara pasang

1. Di bagian Releases, unduh `Soundmate-v2.6.apk`.
2. Buka file tersebut. Jika diminta, izinkan pemasangan dari sumber ini.
3. Jika muncul peringatan Play Protect, pilih opsi untuk tetap memasang. Soundmate belum tersedia di Play Store.
4. Ketuk Pasang.

## Cara pakai

1. Buka Soundmate dan izinkan notifikasi jika diminta.
2. Sambungkan headset atau speaker Bluetooth. Efek aktif otomatis.
3. Pilih preset, atau atur sendiri dengan penggeser dan equalizer.
4. Tekan lama Kustom 1 atau Kustom 2 untuk menyimpan pengaturan sekarang. Ketuk untuk memakainya lagi.
5. Kalau efek belum terasa, hentikan lagu lalu putar lagi setelah Soundmate aktif.

## Izin yang dipakai

- Layanan latar depan (FOREGROUND_SERVICE): menjaga efek tetap berjalan saat layar mati.
- Notifikasi (POST_NOTIFICATIONS): menampilkan status efek.
- Berjalan setelah HP menyala (RECEIVE_BOOT_COMPLETED): menyalakan efek lagi setelah HP dihidupkan ulang, jika efek sebelumnya diaktifkan.
- Mengatur audio (MODIFY_AUDIO_SETTINGS): mengubah pengaturan suara.
- DUMP (opsional): hanya untuk Mode semua aplikasi.

## Mode semua aplikasi (opsional)

Mode ini memasang efek ke semua aplikasi yang mengeluarkan suara. Izin DUMP hanya bisa diberikan dari komputer lewat ADB:

```
adb shell pm grant com.skypin.soundmate android.permission.DUMP
```

Mode ini tidak berjalan di semua HP. Tanpa izin ini, Soundmate tetap berjalan, hanya Mode semua aplikasi yang tidak aktif.

## Batasan

- Ini bukan Dolby Atmos asli. Hasilnya bergantung pada headset, speaker, dan HP.
- Setiap perangkat punya karakter suara sendiri, jadi atur penggeser sesuai selera.

## Memperbarui dan mencopot

- Untuk memperbarui, unduh versi baru lalu pasang di atas versi lama. Pengaturan tetap tersimpan.
- Untuk mencopot, tekan lama ikon Soundmate lalu pilih Copot.

## Kode sumber dan masalah

Repo ini hanya berisi APK dan keterangan. Kode sumber tidak dibagikan di sini. Kalau menemukan masalah, tulis di tab Issues.

Dibuat oleh skypin969.
