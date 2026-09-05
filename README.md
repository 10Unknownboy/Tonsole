# Tonsole.GGs

A modern, fast, and responsive web application for discovering and exploring games. Tonsole.GGs offers an intuitive interface to browse through a library of classic and popular games, complete with an engaging animated user interface and detailed game profiles.

## Features

- **Interactive Game Library**: Browse a curated list of games with smooth hover-to-flip card animations.
- **Real-time Search**: Instantly filter games by title or description.
- **Detailed Game Profiles**: View in-depth information about individual games through dedicated detail pages.
- **Modern User Interface**: Designed with Tailwind CSS and shadcn/ui, featuring glassmorphism elements, custom animations, and responsive layouts.
- **Optimized Performance**: Built on top of Vite and React for lightning-fast loading and hot module replacement during development.

## Tech Stack

- **Framework**: React 18
- **Build Tool**: Vite
- **Language**: TypeScript
- **Routing**: React Router
- **Styling**: Tailwind CSS
- **Component Library**: shadcn/ui (Radix UI primitives)
- **State Management**: React Query (TanStack Query)
- **Icons**: Lucide React

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have Node.js and npm installed. We recommend using a node version manager like `nvm` to manage your Node.js versions.

### Installation

1. Clone the repository:
   ```sh
   git clone <YOUR_GIT_URL>
   cd Tonsole
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm run dev
   ```

The application will be available at `http://localhost:5173` (or the port specified by Vite in your terminal).

## Project Structure

- `/src/components`: Reusable UI components, including the interactive `GameCard` and shadcn/ui primitives.
- `/src/pages`: Main application views (`Index.tsx` for the home page, `GameDetail.tsx` for game-specific views, and `NotFound.tsx`).
- `/src/hooks`: Custom React hooks.
- `/src/lib`: Utility functions and helper classes.
- `/src/App.tsx`: Main application component configuring routing and global providers.
- `/src/index.css`: Global styles, Tailwind directives, and custom animation keyframes.

## Scripts

- `npm run dev`: Starts the local development server.
- `npm run build`: Compiles the application for production.
- `npm run preview`: Bootstraps a local web server to preview the production build.
- `npm run lint`: Runs ESLint to statically analyze the code and find problems.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open-source.
