# ThinkBoard



https://github.com/user-attachments/assets/e21279ea-361a-4816-a611-556d10977127



ThinkBoard, notlarınızı kolayca oluşturup yönetebileceğiniz, MERN stack (MongoDB, Express, React, Node.js) tabanlı bir not uygulamasıdır.

## Özellikler

- Not ekleme, düzenleme ve silme
- Notların listelenmesi ve detay sayfası
- Rate limit (istek sınırlandırma) desteği
- Modern ve responsive arayüz (TailwindCSS + DaisyUI)
- API ile frontend-backend ayrımı

## Kurulum

### 1. Depoyu Klonla

```sh
git clone https://github.com/33Yasin/mern-thinkboard.git
cd mern-thinkboard
```

### 2. Backend Kurulumu

```sh
cd backend
npm install
```

`.env` dosyasını oluşturup aşağıdaki gibi doldurun:

```
MONGO_URI=YOUR_MONGODB_URI
PORT=5001
UPSTASH_REDIS_REST_URL=YOUR_UPSTASH_URL
UPSTASH_REDIS_REST_TOKEN=YOUR_UPSTASH_TOKEN
NODE_ENV=development
```

### 3. Frontend Kurulumu

```sh
cd ../frontend
npm install
```

### 4. Uygulamayı Çalıştır

#### Backend

```sh
cd backend
npm run dev
```

#### Frontend

```sh
cd frontend
npm run dev
```

## Kullanılan Teknolojiler

- React
- Vite
- TailwindCSS & DaisyUI
- Express.js
- MongoDB & Mongoose
- Upstash Redis (Rate Limiting)
- Axios

## Komutlar

Kök dizinde:

- `npm run build` : Frontend'i derler ve bağımlılıkları yükler.
- `npm run start` : Sadece backend'i başlatır.

Frontend dizininde:

- `npm run dev` : Geliştirme sunucusunu başlatır.
- `npm run build` : Frontend'i üretime hazır hale getirir.

Backend dizininde:

- `npm run dev` : Backend'i nodemon ile başlatır.
- `npm run start` : Backend'i başlatır.

## Lisans

ISC
