# RT/RW Administration App

Aplikasi administrasi RT/RW berbasis web menggunakan React untuk frontend dan Express/MongoDB untuk backend lokal.

## Struktur Proyek

```
rt-rw-admin-app/
├─ client/
│   ├─ src/
│   │   ├─ App.js
│   │   ├─ api.js
│   │   ├─ components/
│   │   │   ├─ ResidentForm.js
│   ├─ package.json
├─ server/
│   ├─ models/
│   │   ├─ Resident.js
│   ├─ routes/
│   │   ├─ residents.js
│   ├─ uploads/              # Folder upload foto (biarkan kosong)
│   ├─ .env.example
│   ├─ package.json
│   ├─ server.js
└─ README.md
```

## Cara Instalasi & Menjalankan

### Backend (server)
1. Masuk ke folder `server`
2. Salin `.env.example` menjadi `.env` dan isi URI MongoDB Anda di dalamnya
3. Jalankan: `npm install`
4. Pastikan MongoDB lokal sudah berjalan
5. Jalankan server: `npm start`

### Frontend (client)
1. Masuk ke folder `client`
2. Jalankan: `npm install`
3. Jalankan React: `npm start`

### Akses
- Frontend: `http://localhost:3000`
- Backend API: `http://localhost:5000/api`

## Fitur
- CRUD Data Warga
- Upload foto warga
- Form input dinamis
- Database MongoDB lokal

## Pengembangan
Untuk menambah fitur lain (UMKM, Hunian, Bantuan, dsb), duplikasi pola model, route, komponen, dan API sesuai kebutuhan.

## Kontribusi
Silakan fork dan buat pull request untuk kontribusi atau penambahan fitur baru.

## Lisensi
Proyek ini dilisensikan di bawah MIT License.
