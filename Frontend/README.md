# Frontend - React App

This directory contains the React web application for the habit tracker analytics interface.

## Technology Stack

- **React** - JavaScript library for building user interfaces
- **React Router** - Client-side routing
- **Axios** - HTTP client for API calls
- **Material-UI** or **Tailwind CSS** - UI components and styling
- **Chart.js** or **Recharts** - Data visualization for analytics

## Setup Instructions

1. Install Node.js dependencies:

   ```bash
   npm install
   ```

2. Create environment file:

   ```bash
   # Create .env file with:
   REACT_APP_API_URL=http://localhost:5000/api
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (one-way operation)

## Features

- User authentication (login/register)
- Habit creation and management
- Progress tracking and analytics
- Data visualization with charts
- Responsive design for mobile and desktop

## Build Instructions

For production deployment:

```bash
npm run build
```

This builds the app for production to the `build` folder. The build is minified and ready to be deployed.

## Folder Structure

```
src/
  components/     # Reusable UI components
  pages/         # Page components
  services/      # API service functions
  hooks/         # Custom React hooks
  utils/         # Utility functions
  styles/        # CSS/SCSS files
  App.js         # Main App component
  index.js       # Entry point
```
