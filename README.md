# Svelte 5 Template Repository

Welcome to the **Svelte 5 Template Repository**! This template provides a comprehensive setup for Svelte 5 with tools like TypeScript, Tailwind CSS, Vite, Docker, and more, making it easy to kick-start your next web application with Svelte's latest features.

## Features

- **Svelte 5**: Leverage Svelte’s latest improvements with Runes and optimized compiler performance.
- **TypeScript**: Enhance type safety and developer experience.
- **Tailwind CSS**: Quickly style your application with utility-first CSS.
- **Vite**: Fast bundling with hot module replacement (HMR) for efficient development.
- **Docker Integration**: Local development environment setup, including a containerized database.
- **Tooling**: Pre-configured with ESLint, Prettier, and Playwright for linting, formatting, and testing.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v20 or higher)
- **Bun** (optional, recommended for managing dependencies)
- **Docker** (for containerized development)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/aiherrera/svelte5-template.git
   cd svelte5-template
   bun i
   bun dev
   ```
2. **Start the Development Server**:
   ```bash
    bun dev
    ```
3. **Open the Application**:
    Visit `http://localhost:5173` in your browser.
4. **Docker Setup**: To run the application with Docker, use the following commands:
    ```bash
    docker-compose up -d
    ```
    This will start the application and the database container.
5. **Testing**: Run tests with Playwright:
    ```bash
    bun test
    ```
6. **Linting and Formatting**: Ensure code quality with ESLint and Prettier:
    ```bash
    bun lint
    ```
7. **Build for Production**: Create a production build with Vite:
    ```bash
    bun build
    ```
8. **Deployment**: Deploy the application to a server or platform of your choice.
9. **Contributing**: Contributions are welcome! Feel free to open issues or submit pull requests.
