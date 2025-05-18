# Angular Test Project

This project is an Angular application created using the Angular CLI. It serves as a starting point for building Angular applications.

## Project Structure

The project consists of the following main directories and files:

- `src/`: Contains the source code for the application.
  - `app/`: Contains the main application components and modules.
    - `app.component.html`: The HTML template for the main application component.
    - `app.component.scss`: Styles specific to the main application component.
    - `app.component.spec.ts`: Unit tests for the main application component.
    - `app.component.ts`: The root component of the application.
    - `app.module.ts`: The root module of the application.
    - `app-routing.module.ts`: Sets up routing for the application.
  - `assets/`: Contains static assets for the application.
    - `.gitkeep`: Ensures the assets directory is tracked by Git.
  - `environments/`: Contains environment configuration files.
    - `environment.ts`: Development environment settings.
    - `environment.prod.ts`: Production environment settings.
  - `favicon.ico`: The favicon for the application.
  - `index.html`: The main HTML file serving as the entry point for the application.
  - `main.ts`: The main entry point for bootstrapping the application.
  - `polyfills.ts`: Polyfills needed for compatibility across different browsers.
  - `styles.scss`: Global styles for the application.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd angular-test
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Run the application:
   ```
   ng serve
   ```

5. Open your browser and navigate to `http://localhost:4200` to see the application in action.

## Testing

To run the unit tests for the application, use the following command:
```
ng test
```

## Build

To build the application for production, use the following command:
```
ng build --prod
```

## License

This project is licensed under the MIT License.