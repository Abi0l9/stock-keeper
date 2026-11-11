# Stock Keeper

An inventory-management frontend built with **React, TypeScript, Redux Toolkit, and Material UI**. The project demonstrates a small business workflow for reviewing stock and navigating sales and purchase records.

## What is implemented

- Stock dashboard and individual stock views
- Sales and purchases screens
- Client-side routing with React Router
- Application state handled with Redux Toolkit
- HTTP requests with Axios
- A local JSON Server API with sample data

## Technology

React 18 · TypeScript · Redux Toolkit · React Router · Material UI · Axios · JSON Server

## Run locally

Prerequisite: Node.js and npm.

```bash
git clone https://github.com/Abi0l9/stock-keeper.git
cd stock-keeper
npm install
npm start
```

The `npm start` script runs the React app and JSON Server together:

- App: http://localhost:3000
- Mock API: http://localhost:3001
- Sample inventory: `db.json`

The application fetches stock data from `http://localhost:3001/store`.

## Code orientation

- `src/components/`: dashboard, navigation, stock, and transaction UI
- `src/reducers/`: Redux state and asynchronous actions
- `src/services/`: HTTP access to stock data
- `src/App.tsx`: application routes
- `db.json`: local demonstration data

## Scope

This repository is a **frontend portfolio project using a mock API**, not a production inventory or accounting service. It illustrates component composition, typed frontend code, state management, routing, and API integration.
