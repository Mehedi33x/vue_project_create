Vue.js Project Setup with Vite

Introduction

This README provides step-by-step instructions on how to create a new Vue.js project using Vite, which is the recommended build tool for modern Vue applications.

Prerequisites

Before starting, ensure you have the following installed:

Node.js (Download from nodejs.org)

npm (comes with Node.js) or Yarn

You can verify the installation by running:

node -v
npm -v

Creating a Vue.js Project

Step 1: Create a New Project

Run the following command in your terminal:

npm create vue@latest my-vue-app

OR using Yarn:

yarn create vue@latest my-vue-app

Step 2: Configure Project Options

The CLI will prompt you with several options:

Add TypeScript? (Yes/No)

Add JSX Support? (Yes/No)

Add Vue Router? (Yes/No)

Add Pinia for state management? (Yes/No)

Add Vitest for unit testing? (Yes/No)

Add Cypress/Playwright for E2E testing? (Yes/No)

Add ESLint for code linting? (Yes/No)

Choose the options as per your project requirements.

Step 3: Navigate to the Project Directory

cd my-vue-app

Step 4: Install Dependencies

npm install

OR using Yarn:

yarn install

Step 5: Start the Development Server

npm run dev

OR using Yarn:

yarn dev

Your Vue app should now be running at http://localhost:5173/.

Additional Commands

Build for Production:

npm run build

Preview Production Build:

npm run preview

Run Linter:

npm run lint

Conclusion

You have successfully set up a Vue.js project using Vite. Happy coding! 🚀