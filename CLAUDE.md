# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a React web application bootstrapped with Create React App (CRA). It uses React 19.2.0 and react-scripts 5.0.1 for build tooling.

## Purpose of application

The application is the web site of the software consultancy Valvet Tech AB.

## Development Commands

- `npm start` - Start development server on http://localhost:3000 with hot reload
- `npm test` - Launch Jest test runner in interactive watch mode
- `npm test -- --coverage` - Run tests with coverage report
- `npm test -- --watchAll=false` - Run all tests once without watch mode
- `npm run build` - Create production build in `build/` folder

## Architecture

### Entry Point
- [src/index.js](src/index.js) - React application entry point, renders `<App />` into the DOM root
- [public/index.html](public/index.html) - HTML template with `<div id="root">` mount point

### Application Structure
- [src/App.js](src/App.js) - Main application component
- [src/App.css](src/App.css) - Application styles
- [src/index.css](src/index.css) - Global styles

### Images
- [images/valvet_logo.png] - The valvet logo
- [images/valvet_logo_transparent.png] - Valvet logo with transparent background

### Testing
- Uses Jest and React Testing Library
- [src/setupTests.js](src/setupTests.js) - Test environment configuration
- Test files use `.test.js` extension (e.g., [src/App.test.js](src/App.test.js))

### Build Configuration
- Build configuration is managed by react-scripts (CRA)
- ESLint extends `react-app` and `react-app/jest` configurations
- Production builds are optimized and minified automatically

## Graphical design

### Colors
- Background color should be #2a2a2c
- Text color should be #ffffff;
- Accent coor should be #caaf7a;