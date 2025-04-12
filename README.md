# Untamable AR Art Experience

An AR-powered interactive art platform allowing artists to upload 2D artworks and attach digital overlays viewable through a mobile app.

## Features

- Web interface for artists to create multi-layered AR-enhanced artworks
- Mobile AR scanner for viewing interactive art experiences
- Support for various media types (images, video, 3D models, text, audio)
- Layer management system with drag-and-drop reordering
- Firebase integration for authentication and file storage
- Responsive design for desktop and mobile use

## Technologies Used

- React frontend with TypeScript
- Express backend
- Firebase Authentication and Storage
- Shadcn UI components
- TanStack Query for data fetching
- Drizzle ORM for database operations
- Tailwind CSS for styling

## Getting Started

### Prerequisites

- Node.js (v18+)
- Firebase account for production use

### Installation

1. Clone the repository
   ```
   git clone <repository-url>
   cd untamable-ar
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Set up environment variables
   Create a `.env` file with the following variables:
   ```
   VITE_FIREBASE_API_KEY=your-firebase-api-key
   VITE_FIREBASE_PROJECT_ID=your-firebase-project-id
   VITE_FIREBASE_APP_ID=your-firebase-app-id
   ```

4. Start the development server
   ```
   npm run dev
   ```

5. Open your browser and navigate to http://localhost:5000

## Project Structure

- `/client` - React frontend
  - `/src/components` - UI components
  - `/src/pages` - Application pages
  - `/src/lib` - Utilities and service connections
- `/server` - Express backend
  - `routes.ts` - API endpoints
  - `storage.ts` - Data persistence logic
- `/shared` - Shared code between client and server
  - `schema.ts` - Database schema and type definitions

## Demo Mode

The application includes a demo mode that allows testing without Firebase credentials. This mode:
- Provides a mock user for authentication
- Handles file uploads locally instead of using Firebase Storage
- Simulates all functionality without external dependencies

## License

[Your chosen license]

## Contributors

[Your name/team]