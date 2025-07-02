# Amber Admin Panel

A modern admin dashboard built with React, Vite, and Material-UI, featuring real-time data visualization and Firebase integration.
The Admin Panel is intended for administrators to manage and monitor the Amber Alert App, overseeing alerts, managing user data, and maintaining the overall system.
Admin Panel: Administrative interface for managing alerts and user data.

admin/: Contains the admin panel code for managing the Amber Alert App.
I didn't know how to upload 2 projects in one repo back then.
## Features

- Modern Material-UI based dashboard
- Real-time data visualization with Chart.js
- Firebase integration for backend services
- Responsive design
- Admin authentication and authorization
- Custom icon support
- Express backend integration
- GitHub Pages deployment support

## Technologies Used

- React 18
- Vite
- Material-UI (MUI)
- Chart.js
- Firebase
- Express.js
- Axios
- React Bootstrap Icons

## Project Structure

```
src/
├── components/     # Reusable UI components
├── contexts/       # React context providers
├── firebase-admin/ # Firebase admin configuration
├── services/       # API and service implementations
├── assets/         # Static assets
└── constant/       # Application constants
```

## Setup

1. Install dependencies:
```bash
npm install
```

2. Configure Firebase:
- Create a Firebase project
- Copy `firebase-admin/config.example.js` to `firebase-admin/config.js`
- Update Firebase credentials in `config.js`

3. Start development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

5. Deploy to GitHub Pages:
```bash
npm run deploy
```

## Development

- Run development server: `npm run dev`
- Build for production: `npm run build`
- Preview production build: `npm run preview`
- Run ESLint: `npm run lint`

## License

This project is private and not open source.
