# GAIN LINE Laravel Starter Kit

A modern, full-stack Laravel starter kit built with Vue 3, Inertia.js, and Tailwind CSS. This kit provides a solid foundation for building sophisticated web applications with a focus on developer experience and modern tooling.

## What It Does

The GAIN LINE Laravel Starter Kit is a comprehensive starter kit that combines Laravel's robust backend capabilities with Vue 3's reactive frontend framework. It leverages Inertia.js to create seamless single-page applications without the complexity of a separate API, while maintaining the benefits of server-side routing and validation.

## Frontend Packages

### Core Framework & Routing
- **Vue 3** (`^3.5.13`) - Progressive JavaScript framework for building user interfaces with composition API
- **Inertia.js Vue 3** (`^2.0.0`) - Enables building SPAs using classic server-side routing and controllers
- **Ziggy JS** (`^2.4.2`) - Provides Laravel named routes in JavaScript for seamless frontend routing

### Styling & UI Components
- **Tailwind CSS** (`^4.1.1`) - Utility-first CSS framework for rapid UI development
- **Tailwind CSS Vite Plugin** (`^4.1.11`) - Official Vite integration for Tailwind CSS v4
- **Reka UI** (`^2.4.1`) - Unstyled, accessible Vue components for building design systems. The internal tooling system is shadcn-vue, components can be added by visiting the shadcn-vue website.
- **Lucide Vue Next** (`^0.468.0`) - Beautiful, customizable SVG icons as Vue components
- **TW Animate CSS** (`^1.2.5`) - Tailwind CSS plugin for animations and transitions

### Utility Libraries
- **VueUse Core** (`^12.8.2`) - Collection of essential Vue composition utilities
- **Class Variance Authority** (`^0.7.1`) - Tool for creating component variants with consistent styling
- **clsx** (`^2.1.1`) - Utility for constructing className strings conditionally
- **Tailwind Merge** (`^3.2.0`) - Merge Tailwind CSS classes without style conflicts

### Build Tools & Development
- **Vite** (`^7.0.4`) - Fast build tool and development server
- **Laravel Vite Plugin** (`^2.0.0`) - Laravel integration for Vite with hot module replacement
- **Vue Vite Plugin** (`^6.0.0`) - Official Vue plugin for Vite
- **TypeScript** (`^5.2.2`) - Typed superset of JavaScript for better development experience
- **Vue TSC** (`^2.2.4`) - TypeScript compiler for Vue single file components

### Code Quality & Formatting
- **ESLint** (`^9.17.0`) - Pluggable JavaScript linter for code quality
- **ESLint Vue Plugin** (`^9.32.0`) - ESLint rules specific to Vue.js
- **Prettier** (`^3.4.2`) - Opinionated code formatter for consistent styling
- **Prettier Tailwind Plugin** (`^0.6.11`) - Automatically sorts Tailwind CSS classes
- **Prettier Organize Imports Plugin** (`^4.1.0`) - Sorts and organizes import statements

### Development Utilities
- **Concurrently** (`^9.0.1`) - Run multiple commands concurrently during development
- **Laravel Vite Plugin Wayfinder** (`^0.1.3`) - Enhanced route discovery for Laravel-Vite integration

## Backend Packages

### Core Framework & Integration
- **Laravel Framework** (`^12.0`) - The latest Laravel framework with modern PHP features
- **Inertia Laravel** (`^2.0`) - Server-side adapter for Inertia.js enabling SPA functionality
- **Ziggy** (`^2.4`) - Laravel package for using named routes in JavaScript frontend

### Data & Permissions
- **Spatie Laravel Data** (`^4.17`) - Powerful data transfer objects with validation and transformation
- **Spatie Laravel Permission** (`^6.21`) - Associate users with permissions and roles in a database
- **Spatie Laravel Enum** (`^3.2`) - Enhanced enum support with additional functionality

### UI & Development Tools
- **InertiaUI Table** (`^2.4`) - Advanced table components for Inertia.js applications
- **Laravel Wayfinder** (`^0.1.6`) - Enhanced route discovery and navigation for Laravel applications
- **Laravel Pennant** (`^1.18`) - Feature flags and A/B testing framework for Laravel

### Development & Utilities
- **Laravel Tinker** (`^2.10.1`) - Interactive REPL for debugging and testing Laravel applications

### Development Dependencies
- **Pest PHP** (`^3.8`) - Modern PHP testing framework with elegant syntax
- **Pest Laravel Plugin** (`^3.2`) - Laravel-specific testing utilities for Pest
- **Laravel Pint** (`^1.18`) - Laravel's opinionated PHP code style fixer
- **Laravel Sail** (`^1.41`) - Docker development environment for Laravel
- **Laravel Pail** (`^1.2.2`) - Real-time log monitoring tool for Laravel applications
- **Collision** (`^8.6`) - Beautiful error reporting for command-line applications
- **Solo Term** (`^0.5.0`) - Enhanced terminal output formatting
- **Faker PHP** (`^1.23`) - Generate fake data for testing and seeding
- **Mockery** (`^1.6`) - Simple yet flexible PHP mock object framework

## Backend Integration

This starter kit is designed to work seamlessly with Laravel's backend features:

- **Modern Laravel 12** - Built on the latest Laravel framework with cutting-edge features
- **Server-Side Routing** - Leverages Laravel's routing system through Inertia.js
- **Advanced Data Handling** - Spatie Data objects for type-safe data transfer and validation
- **Permissions System** - Ready-to-use role and permission management
- **Feature Flags** - Laravel Pennant for controlled feature rollouts
- **Enhanced Testing** - Pest PHP framework for modern, readable tests

## Getting Started

1. Install PHP dependencies: `composer install`
2. Install Node.js dependencies: `npm install`
3. Start development servers: `npm run dev`
4. Build for production: `npm run build`

## Available Scripts

### Composer Scripts
- `composer dev` - Start full development environment (server, queue, logs, and Vite)
- `composer dev:ssr` - Start development with server-side rendering enabled
- `composer test` - Run the application test suite with Pest PHP

### NPM Scripts
- `npm run dev` - Start Vite development server with hot reload
- `npm run build` - Build assets for production
- `npm run build:ssr` - Build assets with server-side rendering support
- `npm run format` - Format code with Prettier
- `npm run format:check` - Check code formatting
- `npm run lint` - Lint and fix code with ESLint

### Solo Scripts
- `php artisan solo` - Runs scripts within a single window. See `config/solo.php` to make changes.

This starter kit provides everything needed to build modern, maintainable web applications with Laravel and Vue 3 utilizing InertiaJS, featuring excellent developer experience and production-ready tooling.
