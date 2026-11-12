# React Learning Repository

A collection of beginner-level React and frontend development exercises built while learning React fundamentals, component composition, state management, props, and Tailwind CSS.

The repository contains separate practice projects rather than one integrated application.

## Projects

| Directory | Concepts covered |
|---|---|
| `01vitereact/` | Vite setup, JSX, React components, `React.createElement()` |
| `02counter/` | React `useState` hook, event handling, conditional state updates |
| `03tailwindprops/` | Tailwind CSS, reusable components, props, default prop values |
| `customReact/` | Basic DOM element creation and a simplified custom rendering function |

## Technologies

- JavaScript
- React 18
- React DOM
- Vite
- Tailwind CSS 3
- HTML and CSS
- npm

## Getting Started

Each Vite project is independent and has its own `package.json`.

For example, to run the counter exercise:

```bash
git clone https://github.com/ikraamasayed/React.git
cd React/02counter
npm install
npm run dev
```

To run another Vite exercise, navigate to its directory first:

```bash
cd ../01vitereact
npm install
npm run dev
```

For the Tailwind exercise:

```bash
cd ../03tailwindprops
npm install
npm run dev
```

Open the local URL printed by Vite in your terminal.

## Learning Objectives

- Understand JSX and how React components are structured.
- Pass data between components using props.
- Manage component state with `useState`.
- Handle user interactions through event handlers.
- Build reusable UI components.
- Apply utility-first styling with Tailwind CSS.
- Understand, at a basic level, how JavaScript can create and insert DOM elements.

## Custom Renderer Experiment

The `customReact/` directory contains a small vanilla JavaScript experiment that creates a DOM element from a JavaScript object.

It is intended to demonstrate the basic idea of translating element descriptions into DOM nodes. It is not a replacement for React and does not implement React's rendering architecture.

## Current Scope and Limitations

This repository is for learning and experimentation. It is not a production-ready frontend application.

It currently does not demonstrate:
- React Router or multi-page navigation
- Backend API integration
- Authentication or authorization
- Form validation and submission workflows
- Automated component or integration tests
- Production deployment

## Future Improvements

- Consolidate duplicate and unused component files.
- Correct component and JSX documentation.
- Add examples for `useEffect`, controlled forms, and API requests.
- Build a small application that consumes a REST API.
- Add basic tests using React Testing Library and Vitest.
- Document each exercise with its own purpose and run instructions.

## Status

Learning repository — React fundamentals and frontend practice.
