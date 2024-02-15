# Overview

This repository contains a web application enabling users to generate SQL queries via the OpenAI API. It encompasses both backend and frontend elements.

This project uses Express backend with the OpenAI API and a React frontend to build a user-friendly web app for generating SQL queries using user input. It allows message input, shows conversation history, and displays generated SQL code.

# Scripts

Inside Project

1. `npm run start:frontend`
2. `npm run start:backend`

## File Descriptions

1. `.env` : Stores OpenAI API keys. This file is not included in the snippet but should be present in the project directory, containing an OPEN_API_KEY variable.

2. `index.ts (Backend)` : TypeScript script setting up a server with Express framework to handle HTTP requests. It imports necessary modules and types, initializes the Express application, adds middleware for CORS and JSON parsing, configures the OpenAI API using the API key from environment variables, defines a route handler for POST requests to "/completions", and starts the server on port 8000.

3. `App.tsx (Frontend)` : Defines the main React component of the application. It imports necessary modules and components, manages state for user input, chat messages, and code output. It defines functions for sending user messages to the server, clearing chat history, and filtering and retrieving the latest code message. It renders JSX elements representing the application structure.

4. `index.css` : CSS file containing styling rules for the application.

5. `CodeDisplay (Component)` : Exports a React component named CodeDisplay. It receives a text prop representing the code to be displayed and renders a code display area.

6. `MessageDisplay (Component)` : Exports a React component named MessageDisplay. It receives a message prop representing a chat message and renders a single chat message.

7. `MessagesDisplay (Component)` : Exports a React component named MessagesDisplay. It receives a userMessages prop representing an array of chat messages and renders a collection of chat messages.

## Screenshots

![1](https://github.com/deepakmardii/sqlgenerator/assets/67671892/8d1b8c83-419d-4959-b918-3f379c36cf7f)
![2](https://github.com/deepakmardii/sqlgenerator/assets/67671892/bc5d7b2a-0693-463c-a220-a60aad9362e7)
![3](https://github.com/deepakmardii/sqlgenerator/assets/67671892/d5942813-61a6-45a7-84c4-d9bd1f1a0d6e)
![4](https://github.com/deepakmardii/sqlgenerator/assets/67671892/a06bfe01-06ab-45d2-9e42-d059f1dd99e4)
