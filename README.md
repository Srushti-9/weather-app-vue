# WeatherApp Vue

WeatherApp Vue is a Vue 3 application that allows users to track the current and future weather conditions of cities. It features a clean interface with real-time weather updates and city management capabilities.

## Features

- Search for cities by name to get current weather information
- View detailed weather forecasts for selected cities
- Save cities for quick access on the home page
- Remove cities from the saved list when no longer needed
- Utilizes skeleton loading for improved user experience during data fetching

## Technologies Used

- Vue 3 (Composition API)
- Vue Router
- Axios for HTTP requests
- Tailwind CSS for styling
- Vite for fast development

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## Skeleton Loading

Skeleton loading is implemented using placeholders to enhance the user experience during data fetching. This technique provides visual feedback to users while waiting for content to load, making the application feel more responsive.

## Dynamic Page Title

The page title dynamically changes based on the route using Vue Router's router.beforeEach method. This ensures that each page's title reflects the current city's weather information, enhancing the overall user experience.

## Teleport Feature

The application utilizes Vue's teleport feature to dynamically render components outside the parent DOM hierarchy. This allows for greater flexibility in component placement and improves the overall organization of the application's structure.

## Code Formatting and Linting

Prettier is used for code formatting, ensuring consistent and clean code across the project. ESLint is used for code linting to enforce code quality standards and identify potential errors or issues.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to contribute to this project.
