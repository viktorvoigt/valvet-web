# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a React web application bootstrapped with Create React App (CRA). It uses React 19.2.0 and react-scripts 5.0.1 for build tooling.

## Purpose of application

The application is the web site of the software consultancy Valvet Tech AB.

The application should showcase technical proficiency. Use as many advanced web development techniques and visual effects as possible.

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
- [public/valvet_logo.png] - The valvet logo
- [public/valvet_logo_transparent.png] - Valvet logo with transparent background
- [public/favicon.ico] - The favicon for valvets website

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
- Accent color should be #caaf7a;

### Styling
- No elements should have rounded corners

### Typography
- The font family should be: Jost, sans-serif

## Content

### Title

The title of the browser window should be Valvet Tech AB.

### Navigation bar

Navigation bar should have two links:
- Detta är Valvet, linking showing the start 
- Kundcase, linking to the customer cases
- Ta kontakt, linking to the footer with the contact info

The links should be aligned top right.

The logo should be on the navigation bar aligned left.

### Main body

The main body can contain:
[content/STARTPAGE.md]
[content/CUSTOMERCASES.md]

Body text should be #ffffff;

### Footer

The footer background should be white. 

It should contain the transparent company logo.

The footer contains contact details, each on a card:

Tom Blohmé
tom.blohme@valvet.tech
+46 (0)760 507153

Christian Palmqvist
christian.palmqvist@valvet.tech
+46 (0)704 979545

Then it contains Valvet's street address:

Valvet Tech AB
Djäknegatan 5, Malmö

The footer also has a link to Valvet's LinkedIn page:

https://www.linkedin.com/company/valvet-tech-ab/

Use the following svg data for linked in link:

```xml
<svg
        class="social-icon"
        height="64px"
        width="64px"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 256 256">
        <g>
          <path
            d="M0 18.338C0 8.216 8.474 0 18.92 0h218.16C247.53 0 256 8.216 256 18.338v219.327C256 247.79 247.53 256 237.08 256H18.92C8.475 256 0 247.791 0 237.668V18.335z"
            stroke="currentColor"
            stroke-width="5"
            fill="none"
          />
          <path
            d="M77.796 214.238V98.986H39.488v115.252H77.8zM58.65 83.253c13.356 0 21.671-8.85 21.671-19.91-.25-11.312-8.315-19.915-21.417-19.915-13.111 0-21.674 8.603-21.674 19.914 0 11.06 8.312 19.91 21.169 19.91h.248zM99 214.238h38.305v-64.355c0-3.44.25-6.889 1.262-9.346 2.768-6.885 9.071-14.012 19.656-14.012 13.858 0 19.405 10.568 19.405 26.063v61.65h38.304v-66.082c0-35.399-18.896-51.872-44.099-51.872-20.663 0-29.738 11.549-34.78 19.415h.255V98.99H99.002c.5 10.812-.003 115.252-.003 115.252z"
            fill="currentColor"
          />
    </g>
</svg>
```





