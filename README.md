
# Weather-app ☀️☁️

A simple weather application built with React, TypeScript, and Vite.

## Description

This project aims to provide users with a straightforward way to check the current weather conditions for a specific location.

## Tech Stack

*   [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
*   [TypeScript](https://www.typescriptlang.org/) - A typed superset of JavaScript that compiles to plain JavaScript.
*   [Vite](https://vitejs.dev/) - A build tool that provides a fast and lean development experience for modern web projects.
*   [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapidly styling custom designs.
*   [Radix UI](https://www.radix-ui.com/) - Unstyled, accessible components for building high-quality user interfaces.
*   [React Query](https://tanstack.com/query/latest) - For managing, caching, and updating asynchronous data in React applications.
*   [Date-fns](https://date-fns.org/) - Modern JavaScript date utility library.
*   [Lucide React](https://lucide.dev/) - Beautifully simple, pixel-perfect icons.
*   [Recharts](https://recharts.org/en-US/) - A composable charting library built on React components.
*   [Sonner](https://sonner.emilkowalski.com/) - An opinionated toast component for React.

## Installation 🛠️

### Prerequisites

*   [Node.js](https://nodejs.org/) (>=18)
*   [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) or [pnpm](https://pnpm.io/)

### Steps

1.  Clone the repository:

    ```bash
    git clone https://github.com/Xtract01/Weather-app.git
    cd Weather-app
    ```

2.  Install dependencies using your preferred package manager:

    ```bash
    npm install # or yarn install or pnpm install
    ```

3.  Create a `.env` file in the root directory and add your API key (if required by the weather API you intend to use).  Example:

    ```
    VITE_WEATHER_API_KEY=your_api_key_here
    ```

4.  Start the development server:

    ```bash
    npm run dev # or yarn dev or pnpm dev
    ```

    This will start the application in development mode. Open your browser and navigate to the address provided in the console (usually `http://localhost:5173/`).

## Key Features ✨

*   **Current Weather:** Display current weather conditions for a given location.
*   **Location Search:**  Allows users to search for weather by city.
*   **Responsive Design:**  The application is designed to work on various screen sizes.
*   **Modern UI:** Utilizes modern UI libraries like Radix UI and Tailwind CSS for a clean and intuitive user experience.
*   **Data Visualization:** Employs Recharts to visualize weather data (e.g., temperature trends).

## API Documentation ℹ️

The application likely uses a third-party weather API to fetch weather data.  You'll need to obtain an API key from the provider you choose.  Common weather API providers include:

*   [OpenWeatherMap](https://openweathermap.org/api)
*   [WeatherAPI.com](https://www.weatherapi.com/)
*   [AccuWeather](https://developer.accuweather.com/)

Refer to the documentation of your chosen API provider for details on endpoints, request parameters, and response formats.  The `src/api` directory likely contains the code responsible for interacting with the weather API.

## Contributing 🤝

Contributions are welcome! Here's how you can contribute to this project:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix:

    ```bash
    git checkout -b feature/your-feature-name
    ```

3.  Make your changes and commit them with descriptive commit messages.
4.  Push your changes to your forked repository.
5.  Create a pull request to the main branch of the original repository.

Please ensure your code adheres to the project's coding standards and includes appropriate tests.

## Contributors

*   [Xtract01](https://github.com/Xtract01)
```
