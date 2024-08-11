# Animotion

Animotion is a Next.js project that demonstrates how to create a responsive navigation bar with smooth animations using `Framer Motion` and modern styling with `Tailwind CSS`.

## Project Structure

- `src/components/NavBar.tsx`: A component for the navigation bar with animated links using `Framer Motion`.
- `src/pages/api/hello.ts`: An API route that returns a simple JSON object.
- `src/pages/_app.tsx`: Custom App component to initialize pages.
- `src/pages/_document.tsx`: Custom Document component to augment the default HTML document.
- `src/pages/index.tsx`: The main landing page with a button to toggle the navigation bar.

## Features

- **Responsive Navigation Bar**: The `NavBar` component includes links that animate into view when toggled.
- **Framer Motion Animations**: Smooth animations using `Framer Motion` for the navigation links.
- **Tailwind CSS**: Styling is done using Tailwind CSS for rapid UI development.
- **Next.js API Route**: A simple API route example at `/api/hello`.

## Getting Started

### Prerequisites

- Node.js (>= 12.x)
- npm or yarn

### Installation

1. Clone the repository:

2. Navigate to the project directory:

3. Install the dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

### Running the Project

1. Start the development server:

   ```bash
   npm run dev
   ```

   or

   ```bash
   yarn dev
   ```

2. Open your browser and go to `http://localhost:3000` to view the project.

### Building for Production

1. Build the project:

   ```bash
   npm run build
   ```

   or

   ```bash
   yarn build
   ```

2. Start the production server:

   ```bash
   npm start
   ```

   or

   ```bash
   yarn start
   ```

### Customizing Tailwind CSS

Tailwind CSS is configured in the `tailwind.config.js` file. You can customize the design system, including colors, fonts, and spacing.

### API Routes

The project includes an example API route located at `src/pages/api/hello.ts`. You can add more API routes in the `src/pages/api` directory.

### Deployment

This project can be deployed on any platform that supports Node.js, such as Vercel, Heroku, or Netlify.

Happy coding with Animotion!
