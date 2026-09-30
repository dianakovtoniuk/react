# React Essentials

A small React application built while working through the core concepts of React: components, JSX, props and state. The app presents these concepts as a simple page with a header and a list of concept cards, and includes a set of code examples prepared for an interactive tabs section.

## Features

- Reusable `Header` component with a randomly chosen description on every render
- `CoreConcept` component that receives its content through props
- Concept data kept separately in `src/data.js`
- `TabButton` component with selected state support, ready to be connected to the examples data

## Tech Stack

- React 19
- Create React App (`react-scripts` 5)
- Plain CSS
- React Testing Library

## Getting Started

### Prerequisites

- Node.js 18 or newer
- npm

### Installation

1. Clone the repository with `git clone https://github.com/dianakovtoniuk/react.git`
2. Go to the project folder with `cd react`
3. Install dependencies with `npm install`
4. Start the development server with `npm start`

The app will be available at http://localhost:3000.

## Available Scripts

- `npm start` runs the app in development mode
- `npm run build` creates an optimized production build in the `build` folder
- `npm test` launches the test runner in watch mode
- `npm run eject` ejects the Create React App configuration (irreversible)

## Project Structure

- `public/` static files and the HTML template
- `src/`
  - `assets/` images used by the components
  - `components/`
    - `header/` `Header` component and its styles
    - `coreConcept.jsx` card for a single React concept
    - `tabButton.jsx` button used for switching between examples
  - `App.jsx` root component
  - `data.js` core concepts and code examples
  - `index.jsx` application entry point
  - `index.css` global styles

## Concepts Covered

- Components and component composition
- JSX and dynamic content
- Passing data with props, including the spread syntax
- Reacting to user actions with event handlers
- State and conditional rendering
