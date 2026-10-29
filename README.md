# LoveFrame — LDR Photo Booth

Starter website photobooth responsif dengan kamera, upload foto, filter, kolase, stiker, dan unduh hasil kolase.

## Cara menjalankan
1. Ekstrak ZIP.
2. Buka `index.html` di browser. Untuk kamera, browser biasanya mensyaratkan **HTTPS atau localhost**.
3. Untuk menjalankan lokal dengan VS Code, gunakan ekstensi Live Server lalu klik **Open with Live Server**.

## Publikasikan agar dapat diakses semua orang
Cara mudah: unggah `index.html` ke GitHub repository, aktifkan **Settings → Pages → Deploy from branch**, pilih branch `main` dan folder `/root`. Setelah deploy, GitHub memberikan URL HTTPS publik. Alternatifnya Netlify atau Vercel.

## Catatan penting tentang kode room
Di starter ini kode room adalah UI/prototipe: kode dapat dibuat, dimasukkan, dan disalin, tetapi **belum menghubungkan dua perangkat secara realtime**. Agar room benar-benar bisa dimasuki pasangan dari perangkat berbeda, perlu backend realtime (misalnya Firebase Firestore atau Supabase Realtime), aturan akses, dan konfigurasi proyek. Website publik saja tidak otomatis membuat sesi lintas perangkat. Jangan menyimpan foto pribadi di server tanpa persetujuan kedua pengguna.

## Fitur
- Kamera browser (butuh izin kamera dan HTTPS/localhost)
- Upload foto dari perangkat
- Filter Original, B&W, Honey, Dreamy, Berry, Cool, Retro
- Layout kolase Solo, Classic, Film Strip, Mini Grid
- Tema frame dan caption
- Stiker/emote pada frame
- Unduh kolase JPG ke perangkat
- Responsive desktop dan HP

Semua pemrosesan foto berjalan di browser dalam versi ini.
