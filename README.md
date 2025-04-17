# Slotify

A full-stack appointment booking platform designed for both business owners and clients.

## Project Structure

```
slotify/
├── packages/
│   ├── web/          # Next.js frontend application
│   └── api/          # NestJS backend application
├── package.json      # Root package.json
└── turbo.json        # Turborepo configuration
```

## Getting Started

### Prerequisites

- Node.js >= 18.0.0
- pnpm (recommended) or npm
- PostgreSQL (for development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/slotify.git
cd slotify
```

2. Install dependencies:
```bash
pnpm install
```

3. Set up environment variables:
```bash
cp packages/web/.env.example packages/web/.env.local
cp packages/api/.env.example packages/api/.env
```

4. Start the development servers:
```bash
pnpm dev
```

This will start both the frontend and backend servers in development mode.

## Development

- Frontend: http://localhost:3000
- Backend: http://localhost:4000

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS, TypeScript
- **Backend**: NestJS, PostgreSQL, Prisma
- **Authentication**: NextAuth.js
- **Deployment**: Vercel (frontend), Railway (backend)

## Features

- Business owner registration and management
- Client booking system
- Real-time availability
- Email notifications
- Admin dashboard
- Mobile-first design

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 