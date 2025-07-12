# Node.js TypeScript Starter Template

A minimal, production-ready Node.js starter template with TypeScript, ESLint, Prettier, and development tools configured out of the box.

## ✨ Features

- **TypeScript 5.8+** - Latest TypeScript with strict type checking
- **ESLint 9+** - Modern ESLint configuration with TypeScript support
- **Prettier** - Code formatting with ESLint integration
- **Nodemon** - Automatic server restart during development
- **Concurrently** - Run multiple commands simultaneously
- **Volta** - Node.js version management (Node 22.17.0, npm 11.4.2)
- **Zero Runtime Dependencies** - Only TypeScript as a dependency
- **Modern ES Modules** - ES6 module system with CommonJS interop
- **Development Workflow** - Hot reload, linting, and formatting

## 🚀 Quick Start

### Prerequisites

- **Node.js 22.17.0+** (recommended to use Volta for version management)
- **npm 11.4.2+**

### Installation

1. **Clone or download this template**

   ```bash
   git clone <repository-url>
   cd node-ts-starter
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

## 📁 Project Structure

```
node-ts-starter/
├── src/
│   └── index.ts          # Main application entry point
├── dist/                 # Compiled JavaScript output (auto-generated)
├── package.json          # Project configuration and scripts
├── tsconfig.json         # TypeScript configuration
├── eslint.config.mjs     # ESLint configuration
├── nodemon.json          # Nodemon configuration
└── README.md            # This file
```

## 🛠️ Available Scripts

| Script                 | Description                                         |
| ---------------------- | --------------------------------------------------- |
| `npm run dev`          | Start development server with hot reload            |
| `npm run build`        | Compile TypeScript to JavaScript                    |
| `npm run start`        | Build and run the application                       |
| `npm run lint`         | Run ESLint to check code quality                    |
| `npm run lint:fix`     | Fix ESLint errors automatically                     |
| `npm run format`       | Format code with Prettier                           |
| `npm run format:check` | Check if code is properly formatted                 |
| `npm run type-check`   | Run TypeScript type checking without emitting files |

## 🔧 Configuration

### TypeScript (`tsconfig.json`)

- **Target**: ES2016
- **Module**: ES6 with Node.js resolution
- **Strict Mode**: Enabled for better type safety
- **Output**: Compiled to `./dist` directory
- **Source**: `./src` directory

### ESLint (`eslint.config.mjs`)

- Modern flat config format
- TypeScript-aware linting rules
- Prettier integration
- Node.js globals support
- Custom rules for better code quality

### Nodemon (`nodemon.json`)

- Watches `dist` directory for changes
- Restarts server on JavaScript file changes
- Optimized for compiled TypeScript output

## 🎯 Development Workflow

1. **Write TypeScript code** in the `src/` directory
2. **Run `npm run dev`** for development with hot reload
3. **Use `npm run lint`** to check code quality
4. **Use `npm run format`** to format code
5. **Build with `npm run build`** for production

## 📝 Getting Started

1. **Replace the content in `src/index.ts`** with your application code:

   ```typescript
   console.log('Hello from your TypeScript Node.js app!');
   ```

2. **Add your source files** to the `src/` directory

3. **Import and use modules** as needed:
   ```typescript
   import { someFunction } from './utils/helpers';
   ```

## 🚀 Production Deployment

1. **Build the application**:

   ```bash
   npm run build
   ```

2. **Start the production server**:

   ```bash
   npm run start
   ```

3. **Or run the compiled JavaScript directly**:
   ```bash
   node ./dist/index.js
   ```

## 🔍 Code Quality

This template includes several tools to maintain high code quality:

- **ESLint**: Catches common errors and enforces coding standards
- **Prettier**: Ensures consistent code formatting
- **TypeScript**: Provides static type checking
- **Strict Mode**: Enables all TypeScript strict checks

## 📦 Adding Dependencies

### Runtime Dependencies

```bash
npm install <package-name>
```

### Development Dependencies

```bash
npm install --save-dev <package-name>
```

## 🎨 Customization

### Adding Environment Variables

Create a `.env` file in the root directory:

```env
NODE_ENV=development
PORT=3000
```

### Adding Express.js

```bash
npm install express
npm install --save-dev @types/express
```

### Adding Testing

```bash
npm install --save-dev jest @types/jest ts-jest
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run linting and formatting
5. Submit a pull request

## 📄 License

This project is licensed under the ISC License.

## 🆘 Support

If you encounter any issues or have questions:

1. Check the [TypeScript documentation](https://www.typescriptlang.org/docs/)
2. Review the [ESLint configuration](https://eslint.org/docs/latest/)
3. Consult the [Node.js documentation](https://nodejs.org/docs/)

---

**Happy coding! 🎉**
