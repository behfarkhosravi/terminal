# Project Name: Terminal

## About the Project
This project is a terminal-style website, designed to mimic the look and feel of a command-line interface. It is forked from the original project by [M4TT72 | Terminal](https://term.m4tt72.com).

### Configuration
- **TypeScript Configuration**: Managed via `tsconfig.json` and `tsconfig.node.json` for different environments.
- **Svelte Configuration**: Managed via `svelte.config.js`.
- **Tailwind Configuration**: Managed via `tailwind.config.js`.
- **Vite Configuration**: Managed via `vite.config.ts`.
- **Docker Configuration**: Managed via `Dockerfile` and `docker-compose.yml`.
- **Apache Configuration**: Managed via `httpd.conf` for server settings.

## Quick Start

### Prerequisites
Ensure you have the following installed on your machine:
- Node.js
- Yarn or npm
- Docker (optional, for containerized deployment)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/terminal.git
   cd terminal
   ```

2. **Install dependencies:**
   ```sh
   yarn install
   # or, using npm
   npm install
   ```

3. **Start the development server:**
   ```sh
   yarn dev
   # or, using npm
   npm run dev
   ```

### Build for Production

To build the project for production, run:

```sh
yarn build
# or, using npm
npm run build
```

### Running with Docker

1. **Build the Docker image:**
   ```sh
   docker build -t terminal .
   ```

2. **Run the Docker container:**
   ```sh
   docker-compose up -d
   ```

## License
This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.