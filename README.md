# RT/RW Administration App

Aplikasi administrasi RT/RW berbasis web (React & Express/MongoDB lokal).

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

## Cara Setup

### Backend (server)
1. Buka folder `server`
2. Salin `.env.example` ke `.env` dan pastikan URI MongoDB sudah benar
3. Jalankan: `npm install`
4. Pastikan MongoDB lokal sudah berjalan
5. Jalankan server: `npm start`

### Frontend (client)
1. Buka folder `client`
2. Jalankan: `npm install`
3. Jalankan React: `npm start`

### Akses
- Frontend: `http://localhost:3000`
- Backend API: `http://localhost:5000/api`

## Fitur
- Data Warga (CRUD)
- Form input & data dinamis
- Database MongoDB lokal

## Pengembangan
- Untuk menambah fitur lain (UMKM, Hunian, Bantuan, dll), duplikasi pola model, route, komponen, dan API sesuai kebutuhan.
