# Cloned and Re-edited

[Electron React Boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate)

## Project Overview

**Name:** Electron React Boilerplate  
**Description:** A foundation for scalable desktop apps  
**License:** MIT  
**Homepage:** [GitHub Repository](https://github.com/electron-react-boilerplate/electron-react-boilerplate#readme)  

## Features and Modifications:

1. **Entry Points:**
   - Customized `main.js` and `renderer.js` files to align with application-specific needs.

2. **Package Metadata:**
   - Updated `package.json` with project name, description, and contributors:
     - **Author:** Electron React Boilerplate Maintainers  
     - **Contributors:** Amila Welihinda ([GitHub](https://github.com/amilajack))

3. **Electron Configuration:**
   - Configured `electron-builder` for multi-platform builds (Windows, macOS, Linux).
   - Added custom installation directories and app icons.

4. **Styling Updates:**
   - Integrated SCSS/SASS for modular and maintainable styling.

5. **React & Redux:**
   - Added Redux for efficient state management.
   - Refactored React components for improved scalability.

6. **API Integration:**
   - Utilized Axios for seamless interaction with external APIs.

7. **Build Optimization:**
   - Enhanced Webpack settings for faster builds and reduced bundle sizes.
   - Implemented production-specific optimizations like tree-shaking and code-splitting.

8. **Testing Enhancements:**
   - Configured Jest and React Testing Library for unit and integration tests.

9. **Custom Scripts:**
   - Added npm scripts for:
     - Development (`npm start`)
     - Production build (`npm run build`)
     - Testing (`npm test`)

10. **Multi-Platform Build:**
    - Configured builds for Windows (NSIS), macOS (DMG), and Linux (AppImage).

## How to Use the Re-edited Boilerplate

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/electron-react-boilerplate/electron-react-boilerplate
   ```

2. **Install Dependencies:**
   ```bash
   cd electron-react-boilerplate
   npm install
   ```

### Development

1. **Run in Development Mode:**
   ```bash
   npm start
   ```

2. **Lint and Fix Code:**
   ```bash
   npm run lint:fix
   ```

### Build

1. **Production Build:**
   ```bash
   npm run build
   ```

2. **Package Application:**
   ```bash
   npm run package
   ```

### Testing

1. **Run Tests:**
   ```bash
   npm test
   ```

## Additional Information

- **Keywords:** Electron, React, TypeScript, SASS, Webpack, Hot Reload
- **Documentation:** Detailed API and usage instructions available in the [repository](https://github.com/electron-react-boilerplate/electron-react-boilerplate#readme).

Feel free to adapt and extend this boilerplate for your desktop application needs!
