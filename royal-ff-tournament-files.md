# Royal FF Tournament - Complete Project Files

## Overview
Royal FF Tournament is a comprehensive Free Fire tournament management platform with blue theme interface.

## Key Features
- Tournament creation and management
- Team formation and registration  
- Real-time leaderboards
- User profiles and statistics
- Admin dashboard
- WebSocket real-time updates
- Blue themed gaming interface

## Main Files Structure

### Frontend (React + TypeScript)
- `client/src/App.tsx` - Main app component with routing
- `client/src/pages/home.tsx` - Homepage with dashboard
- `client/src/pages/tournaments.tsx` - Tournament listing
- `client/src/pages/create-tournament.tsx` - Tournament creation
- `client/src/pages/teams.tsx` - Team management
- `client/src/pages/profile.tsx` - User profile
- `client/src/pages/admin.tsx` - Admin dashboard
- `client/src/components/navigation.tsx` - Header navigation
- `client/src/components/bottom-nav.tsx` - Mobile navigation
- `client/src/components/tournament-card.tsx` - Tournament display
- `client/src/components/leaderboard.tsx` - Rankings display
- `client/src/components/bracket-view.tsx` - Tournament brackets
- `client/src/index.css` - Blue theme styling

### Backend (Express + TypeScript)
- `server/index.ts` - Main server file
- `server/routes.ts` - API routes and WebSocket
- `server/storage.ts` - Database operations
- `server/db.ts` - Database connection
- `shared/schema.ts` - Database schema and types

### Configuration
- `package.json` - Dependencies and scripts
- `vite.config.ts` - Build configuration
- `tailwind.config.ts` - CSS framework config
- `drizzle.config.ts` - Database migration config
- `tsconfig.json` - TypeScript configuration

## Installation Instructions
1. npm install
2. Set up PostgreSQL database
3. npm run db:push
4. npm run dev

## Features Included
✓ Crown logo and Royal FF Tournament branding
✓ Blue color theme throughout interface
✓ Tournament management system
✓ Team creation and management
✓ Real-time WebSocket updates
✓ User authentication system
✓ Admin dashboard
✓ Mobile responsive design
✓ No daily rewards feature (removed as requested)

## Database Schema
- Users table with game statistics
- Tournaments with various formats
- Teams and team members
- Tournament registrations
- Matches and results
- Leaderboards and rankings
- Notifications system

The complete source code is available in the workspace directory.