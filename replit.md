# Royal FF Tournament - Free Fire Tournament Platform

## Overview
Royal FF Tournament is a full-stack web application designed for organizing and managing Free Fire esports tournaments. The platform allows users to create tournaments, form teams, register for competitions, and track leaderboards with real-time updates.

## System Architecture
The application follows a modern full-stack architecture with clear separation between frontend, backend, and database layers:

- **Frontend**: React-based single-page application with TypeScript
- **Backend**: Express.js REST API with WebSocket support
- **Database**: PostgreSQL with Drizzle ORM
- **Build System**: Vite for frontend bundling and development
- **Deployment**: Replit-optimized with autoscale deployment

## Key Components

### Frontend Architecture
- **Framework**: React 18 with TypeScript
- **UI Library**: shadcn/ui components built on Radix UI primitives
- **Styling**: Tailwind CSS with custom gaming theme colors
- **Routing**: Wouter for client-side routing
- **State Management**: TanStack Query for server state management
- **Form Handling**: React Hook Form with Zod validation
- **Real-time Updates**: WebSocket client integration

### Backend Architecture
- **Server**: Express.js with TypeScript
- **Database ORM**: Drizzle ORM for type-safe database operations
- **Database**: PostgreSQL (using Neon serverless)
- **Real-time**: WebSocket server for live tournament updates
- **Session Management**: Express sessions with PostgreSQL storage
- **API Design**: RESTful endpoints with proper error handling

### Database Schema
The application uses a comprehensive schema supporting:
- **Users**: Player profiles with game statistics and authentication
- **Tournaments**: Tournament management with various formats and statuses
- **Teams**: Team formation and member management
- **Matches**: Tournament bracket system with match results
- **Leaderboards**: Global and tournament-specific rankings
- **Notifications**: Real-time user notifications

## Data Flow
1. **Client Requests**: Frontend makes API calls through TanStack Query
2. **API Processing**: Express routes handle business logic and database operations
3. **Database Operations**: Drizzle ORM provides type-safe database interactions
4. **Real-time Updates**: WebSocket broadcasts tournament updates to connected clients
5. **State Management**: Client-side state is synchronized with server data

## External Dependencies
- **Database**: Neon PostgreSQL for serverless database hosting
- **UI Components**: Radix UI primitives for accessible component foundation
- **Styling**: Tailwind CSS for utility-first styling approach
- **Development**: Vite development server with hot module replacement
- **TypeScript**: Full type safety across frontend and backend

## Deployment Strategy
- **Platform**: Replit with autoscale deployment target
- **Build Process**: Vite builds the frontend, esbuild bundles the backend
- **Development**: Integrated development environment with hot reloading
- **Database**: Automatic PostgreSQL provisioning through Replit modules
- **Environment**: Node.js 20 runtime with web and PostgreSQL modules

## Changelog
- June 24, 2025. Initial setup
- June 24, 2025. Changed branding from FireTournament to GameArena with gamepad logo
- June 24, 2025. Updated branding to Royal FF Tournament with crown logo, removed daily rewards feature

## User Preferences
Preferred communication style: Simple, everyday language.