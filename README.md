# Skill Link Backend

Node.js + Express backend for the Skill Link platform.

## Stack
- Node.js
- Express
- MongoDB / Mongoose
- JWT authentication
- Socket.IO
- Multer
- Express Validator
- CORS

## Setup

```bash
cd backend
npm install
```

Create `.env` from `.env.example` and add your own local credentials.

Start the development server:

```bash
npm run dev
```

The API health endpoint is:

`GET /api/health`

## Security
Never commit `.env`, API tokens, phone credentials, JWT secrets, or other private keys.
