# GatePlate Frontend

This is the frontend application for the GatePlate ALPR (Automatic License Plate Recognition) system. It provides a modern, responsive user interface for monitoring and managing the system.

## Features
- **Photo & Video Recognition UI:** A modern interface to upload images or select video streams for real-time license plate recognition.
- **System Status Dashboard:** Real-time monitoring dashboard displaying backend CPU, RAM, and AI pipeline loads via WebSockets.
- **Guest Registration:** An administrative interface to register and manage temporary access for guest vehicles.
- **Payment Integration:** Embedded WayForPay widget for purchasing API keys to increase recognition limits.

## Tech Stack
- **Framework:** React
- **Styling:** CSS (Vanilla / Modules)
- **WebSockets:** Native WebSocket API integration for real-time metric streams

## Installation & Setup

1. **Install dependencies:**
   Make sure you have Node.js installed.
   ```bash
   npm install
   # or
   yarn install
   ```

2. **Set up Environment Variables:**
   Create a `.env` file in the root directory (if needed) and specify the backend API URL.
   ```env
   REACT_APP_API_URL=http://localhost:8000
   ```

3. **Run the development server:**
   ```bash
   npm start
   # or
   npm run dev
   ```
   The application will run locally at `http://localhost:3000`.

## Building for Production
To build the application for a production environment:
```bash
npm run build
```
