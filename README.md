# Discord Clone

A full-stack **Discord-inspired chat app** built with [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), [React](https://react.dev/), [postgres.js](https://github.com/porsager/postgres), and [Supabase](https://supabase.com/) DB.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- **Instant Messaging** between users and servers (rooms)
- **Authentication** via Supabase and NextAuth.js
- **Real-time database updates** and presence (Online/Offline) features
- **Responsive UI** built with Tailwind CSS
- **Dark mode** switch
- **CRUD operations** for messages, servers, and users
- **React to messages** from friends & servers
- **Media upload** (images/attachments)
- **User presence indicator:** Online status
- **Custom server creation**
- **User Profile customization**
- **Terms of Service** (just as a prop)
- ...and more

## Tech Stack

**Frontend:** Next.js (App Router), React, Tailwind CSS  
**Backend:** Next.js API routes, postgres.js  
**Database:** Supabase (PostgreSQL)  
**Auth:** NextAuth.js, Supabase Auth

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- Supabase project & API keys

### Installation

```bash
git clone https://github.com/calvintaw/discord_clone.git
cd discord_clone
npm install
```

### Environment Variables

Create a `.env.local` file in the root and add your credentials:

```
SUPABASE_URL=your-supabase-url
SUPABASE_ANON_KEY=your-supabase-anon-key
DATABASE_URL=your-postgres-connection-string
NEXTAUTH_SECRET=your-nextauth-secret
```

### Running Locally

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

Main folders and their purpose:

```
📁app
 ├── (auth)         # Authentication pages (login, register, terms)
 ├── (root)         # Main app pages (chat, dashboard, discover, news, test)
 ├── api            # Backend API routes (auth, seed, theme)
 ├── lib            # Hooks, helpers, context, Supabase, etc.
 ├── ui             # Modular UI components: chat, contact, form, general, news, sidebar
 ├── globals.css    # Global styles
 ├── store.ts       # State management
 └── types.d.ts     # TypeScript types
```

## Screenshots

### Home Page
<img width="1315" height="653" alt="Home Page Screenshot" src="https://github.com/user-attachments/assets/be179c2d-6d9d-465b-8092-4cf03f29bcb5" />

### Chat Room
<img width="1316" height="648" alt="Chat Room Screenshot" src="https://github.com/user-attachments/assets/a7de3e11-1f8a-4a12-8c79-755e03290b66" />

### Servers
<img width="1314" height="647" alt="Servers Screenshot" src="https://github.com/user-attachments/assets/5acf766f-900c-4943-be37-3777af9a88a1" />

## Contributing

Pull requests are welcome (sorry in advance for my code if you want to contribute). For major changes, please open an issue to discuss what you’d like to change.

## License

[MIT](LICENSE)

## Contact

Created by [@calvintaw](https://github.com/calvintaw)  
Feel free to reach out!
