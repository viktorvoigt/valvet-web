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

### Styling
- No elements should have rounded corners

### Typography
- Sans serif fonts should be used

## Content

### Main page

The main page should contain the following text:

"Konsultmässighet i ryggraden, teknik i hjärnan, kunden i hjärtat och nyfikenhet i armar och ben"

"Detta är Valvet"

"Valvet har ambitionen att verka som södra Sveriges främsta
konsultbolag inom bank, finans, försäkring och fintech. Våra kunder
finns huvudsakligen inom dessa segment och våra konsulter har rätt
kunskap och erfarenhet för att leverera excellens i sina uppdrag."

"Vi erbjuder"

"Det värde vi kan erbjuda våra kunder blir därmed unikt och varje
enskild konsult är handplockad till vårt team som består av de
absolut främsta konsulterna på marknaden."

"Våra konsulter"

"Som konsult hos oss strävar du efter att förbättra både din egen
prestation och kvaliteten på det arbete du levererar, men
framförallt skapa verkliga och varaktiga värden för våra kunder
genom innovativa lösningar och enastående service. Samtidigt
värdesätter vi att du har roligt på jobbet och trivs i din roll,
eftersom vi tror på att glädje och engagemang är nyckeln till
framgång."

### Footer

The footer contains contact details:

Tom Blohmé
+46 (0)760 507153

Christian Palmqvist
+46 (0)704 979545

Then is contains Valvets street adress:

Valvet Tech AB
Djäknegatan 5, Malmö

The footer also has a link to vavets linked in page:

https://www.linkedin.com/company/valvet-tech-ab/






