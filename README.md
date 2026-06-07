# Behzod Avtoustoz

O'zbekistonda haydovchilik imtihoniga professional tayyorgarlik platformasi (monorepo).

## Tuzilma

```
behzod-avtoustoz/
├── frontend/   # React.js + Tailwind CSS (mijoz qismi)
└── backend/    # Node.js + Express + MongoDB (server qismi)
```

## Texnologiyalar

| Qism | Texnologiya |
|------|-------------|
| Frontend | React 18, Redux Toolkit, Tailwind CSS, i18next, Socket.io-client |
| Backend | Node.js, Express, MongoDB (Mongoose), Socket.io, JWT |
| To'lov | Click, Payme |
| SMS | Eskiz.uz |

## Tez ishga tushirish

### 1. Backend
```bash
cd backend
npm install
cp .env.example .env      # va qiymatlarni to'ldiring
npm run seed              # boshlang'ich ma'lumot (admin + namuna savollar)
npm run dev               # http://localhost:5000
```

### 2. Frontend
```bash
cd frontend
npm install
npm start                 # http://localhost:3000
```

## Hujjatlar

- Backend API va sozlamalar: [`backend/README.md`](backend/README.md)

## Litsenziya

Private — Barcha huquqlar himoyalangan.
