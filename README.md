# Slotify - Appointment Booking Platform

Slotify is a modern, full-stack appointment booking platform that connects businesses with clients. Built with Next.js, TypeScript, and Prisma, it provides a seamless experience for both business owners and their clients.

## Features

### For Businesses
- Create and manage your business profile
- Set up service offerings and availability
- Handle appointment bookings and cancellations
- Manage client relationships
- View booking analytics

### For Clients
- Search and discover local businesses
- Book appointments online
- Manage your appointments
- Save favorite businesses
- Receive booking notifications

## Tech Stack

- **Frontend**: Next.js 14, TypeScript, Tailwind CSS, Headless UI
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: NextAuth.js
- **File Storage**: Local file system with API routes
- **Real-time Updates**: WebSocket support

## Getting Started

### Prerequisites

- Node.js 18+ 
- PostgreSQL
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/adammatar/Slotify.git
cd Slotify
```

2. Install dependencies:
```bash
# Install root dependencies
npm install

# Install API dependencies
cd packages/api
npm install

# Install web dependencies
cd ../web
npm install
```

3. Set up environment variables:
```bash
# In packages/api
cp .env.example .env

# In packages/web
cp .env.example .env
```

4. Set up the database:
```bash
cd packages/web
npx prisma migrate dev
```

5. Start the development servers:
```bash
# Start API server
cd packages/api
npm run dev

# Start web server
cd ../web
npm run dev
```

## Project Structure

```
Slotify/
├── packages/
│   ├── api/          # Backend API
│   └── web/          # Frontend application
├── .gitignore
├── package.json
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Adam Matar - [@adammatar](https://github.com/adammatar)

Project Link: [https://github.com/adammatar/Slotify](https://github.com/adammatar/Slotify) 