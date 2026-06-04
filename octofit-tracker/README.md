# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Express, TypeScript, and MongoDB.

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
│   ├── src/
│   ├── package.json
│   ├── vite.config.ts
│   └── tsconfig.json
└── backend/           # Node.js + Express + TypeScript API
    ├── src/
    ├── package.json
    └── tsconfig.json
```

## Technology Stack

### Frontend
- **React 19** - UI library
- **Vite** - Build tool and dev server
- **TypeScript** - Type-safe JavaScript
- **Port**: 5173

### Backend
- **Node.js** - Runtime
- **Express** - Web framework
- **TypeScript** - Type-safe development
- **Mongoose** - MongoDB ODM
- **Port**: 8000

### Database
- **MongoDB** - NoSQL database
- **Port**: 27017

## Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB (running on localhost:27017)

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

The API will be available at `http://localhost:8000`

### MongoDB Setup

Ensure MongoDB is running:

```bash
# Using Docker
docker run -d -p 27017:27017 --name mongodb mongo:latest

# Or using MongoDB Community Edition locally
mongod
```

## API Endpoints

- `GET /` - Welcome message
- `GET /api/health` - Health check

## Development

### Frontend Development
```bash
cd frontend
npm run dev    # Start dev server
npm run build  # Build for production
npm run lint   # Run linter
```

### Backend Development
```bash
cd backend
npm run dev    # Start dev server with ts-node
npm run build  # Compile TypeScript
npm run watch  # Watch for changes
npm start      # Run compiled version
```

## License

ISC
