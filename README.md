# EAYL Demo - Modern Express.js TypeScript App

A simple, modern Express.js application built with TypeScript, using tsx for development and ES modules.

## Features

- ⚡ **Modern Setup**: Uses ES modules and latest TypeScript features
- 🚀 **Fast Development**: Uses `tsx` for instant TypeScript execution without compilation
- 📦 **Type Safety**: Full TypeScript support with Express types
- 🏗️ **Production Ready**: Proper build process for production deployment

## Quick Start

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
# Clone and install dependencies
git clone <your-repo-url>
cd eayl-demo
npm install
```

### Development

```bash
# Start development server with hot reload
npm run dev
```

The server will start at `http://localhost:3000`

### Production

```bash
# Build the application
npm run build

# Start production server
npm start
```

## Available Scripts

- `npm run dev` - Start development server with tsx
- `npm run build` - Build TypeScript to JavaScript
- `npm start` - Start production server
- `npm run clean` - Remove build directory

## API Endpoints

- `GET /` - Welcome message with timestamp
- `GET /health` - Health check endpoint
- `GET /api/users/:id` - Get user by ID (example route)

## Project Structure

```
├── src/
│   └── index.ts          # Main application file
├── dist/                 # Compiled JavaScript (after build)
├── package.json
├── tsconfig.json         # TypeScript configuration
├── .env.example          # Environment variables example
└── README.md
```

## Environment Variables

Copy `.env.example` to `.env` and adjust the values:

```bash
cp .env.example .env
```

- `PORT` - Server port (default: 3000)
- `NODE_ENV` - Environment mode (development/production)

## Technologies Used

- **Express.js** - Web framework
- **TypeScript** - Type-safe JavaScript
- **tsx** - TypeScript execution engine
- **ES Modules** - Modern module system
- **Node.js** - Runtime environment