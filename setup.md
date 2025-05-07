# Development Setup

## Prerequisites

- Node.js (LTS)
- Expo CLI (`npm install -g expo-cli`)
- Supabase account
- Firebase account (if used)

## Environment Variables

Create a `.env` file in the root with the following keys:

```
SUPABASE_URL=
SUPABASE_ANON_KEY=
FIREBASE_API_KEY=
FIREBASE_AUTH_DOMAIN=
...
```

## Running the App

```bash
cd apps/mobile
npm install
npx expo start
```

To run web:

```bash
cd apps/web
npm install
npm run dev
```
