# Project Architecture

## File Structure

```
itsymixsy/
├── apps/
│   ├── mobile/              # Expo React Native app
│   └── web/                 # React or Next.js app
├── backend/
│   ├── supabase/            # Supabase schema + edge functions
│   └── firebase/            # Optional Firebase functions
├── admin/
│   └── appmaster/           # CMS configs or workflows
├── docs/                    # Development documentation
├── .env                     # Local environment secrets
├── README.md
```

## Services Overview

- **Supabase** handles user auth, data (PostgreSQL), and file uploads
- **Expo** runs the mobile app with Firebase/Supabase integration
- **AppMaster** or **Supabase Studio** used for backend and business management
- **Vercel/Netlify** host the web app
