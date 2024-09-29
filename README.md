# bun-hbs-pkg-builder: Handlebars Integration for BunJs

This project creates a robust library for seamlessly integrating Handlebars templates into BunJs applications. It provides a powerful and flexible templating solution optimized for the Bun runtime. bun-hbs-pkg-builder serves as the core engine for creating the Bun-Hbs library, containing the essential source files and implementation details necessary for the library's functionality.

The engine includes key components such as template rendering, caching mechanisms, and configuration management, which form the foundation of the Bun-Hbs library. By leveraging this engine, developers can easily build and customize their own Handlebars integration for BunJs projects.

## Create a new package

```bash
bun init
bun install
```

```bash
npm run build
```

Copy the package.json and README.md to dist folder.

## Key Features

- **Efficient Template Rendering**: Utilizes Handlebars for fast and flexible template processing.
- **Caching Mechanism**: Implements an intelligent caching system to optimize performance.
- **Configurable**: Offers easy configuration options for views, partials, and layouts directories.
- **TypeScript Support**: Fully written in TypeScript for enhanced developer experience and type safety.
- **Custom Helpers**: Allows registration of custom Handlebars helpers for extended functionality.
- **Layout Support**: Enables the use of layout templates for consistent page structures.
- **Error Handling**: Implements comprehensive error handling and logging for easier debugging.

## Implementation Details

- The library is built using TypeScript and targets ES2022.
- It leverages Bun's build system for efficient compilation and bundling.
- The main functionality is encapsulated in the `engine.ts` file, which handles template rendering, caching, and helper registration.
- Configuration management is handled separately in `config.ts` for improved modularity.
- The project structure follows best practices for creating npm packages, with clear separation of source code and distribution files.

## Usage

Developers can easily integrate this library into their BunJs projects:

1. Install the package: `bun add bun-hbs`
2. Configure the template directories and log level.
3. Initialize the Handlebars engine.
4. Use the `render` function to process templates within their application.

## Building and Publishing

The project uses the following build process:

1. TypeScript compilation for type checking and declaration file generation.
2. Bun's build system for creating the final JavaScript bundle.

This approach ensures compatibility with both CommonJS and ES modules, making the library versatile for different project setups.

## Future Enhancements

- Implement unit tests to ensure reliability and ease future development.
- Add more advanced caching strategies for improved performance in high-load scenarios.
- Explore integration with Bun-specific features for further optimization.

This library aims to provide a seamless experience for developers looking to use Handlebars templates in their BunJs projects, combining the speed of Bun with the flexibility of Handlebars.

MIT