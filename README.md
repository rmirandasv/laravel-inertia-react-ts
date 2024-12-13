# Laravel Inertia React TypeScript Starter Template

This template is designed to streamline the creation of Laravel applications with a modern tech stack: **Laravel + Inertia.js + React + TypeScript**. It includes pre-configured tools like ESLint, Prettier, and Vite, as well as TailwindCSS. This setup saves time and avoids the confusion of configuring these tools manually.

## Features

- **Laravel** 11.x with Inertia.js for seamless server-driven React apps.
- **React** 18.x with TypeScript for modern, type-safe development.
- **Vite** for fast and efficient builds.
- **TailwindCSS** for utility-first CSS styling.
- **ESLint** and **Prettier** pre-configured for consistent and clean code.
- **Pest** for elegant testing.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- PHP ^8.2
- Composer
- Node.js (>= 16.x)
- npm or Yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/rmirandasv/laravel-inertia-react-ts.git my-project
   cd my-project
   ```

2. **Install PHP dependencies**

   ```bash
   composer install
   ```

3. **Install JavaScript dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

4. **Set up the environment file**

   Copy `.env.example` to `.env` and configure your environment variables:

   ```bash
   cp .env.example .env
   ```

5. **Generate the application key**

   ```bash
   php artisan key:generate
   ```

6. **Run the migrations**

   ```bash
   php artisan migrate
   ```

7. **Start the development server**

   Use `concurrently` to start both the backend and Vite dev server:

   ```bash
   npm run dev
   ```

### npm Scripts

- `npm run dev`: Start the Laravel server and Vite development server.
- `npm run build`: Build assets for production.
- `npm run lint`: Run ESLint to check for issues.

## Dependencies

### PHP (Composer) Dependencies

- **`laravel/framework`**: Core Laravel framework.
- **`inertiajs/inertia-laravel`**: Inertia.js server-side adapter.
- **`laravel/sail`**: Local development environment.
- **`pestphp/pest`**: Testing framework.
- **`laravel/pint`**: Code style fixer.

### JavaScript (npm) Dependencies

#### Production

- **`@inertiajs/react`**: Inertia.js client-side adapter for React.
- **`react` & `react-dom`**: React library and DOM renderer.
- **`@vitejs/plugin-react`**: Vite plugin for React.

#### Development

- **`eslint` & plugins**: Linting tools for maintaining code quality.
- **`prettier`**: Code formatter.
- **`tailwindcss`**: CSS framework.
- **`vite`**: Build tool.

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests to enhance this template.

## License

This project is open-sourced software licensed under the [MIT license](LICENSE).

---

Enjoy coding with this Laravel Inertia React TypeScript starter template!

