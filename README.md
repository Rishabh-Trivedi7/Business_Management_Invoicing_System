# Business Management Invoicing System

## Overview
A full-stack invoicing and business management application built with React, Vite, Node.js, Express, and MongoDB. The system allows users to manage invoices, track ledger entries, and handle authentication securely.

## Authors
- Project Team / Contributors
- Kahan Shah 
- Rishabh Trivedi

## Functionality
- User authentication, registration, and secure login
- Invoice creation, listing, preview, and detailed viewing
- Automated invoice number generation
- Business ledger tracking and management
- Support for billing calculations and invoice services
- Backend API with Express, Firebase Admin integration, JWT authentication, and MongoDB data storage
- Frontend React app with responsive UI and routing

## File Structure
- `client/` - React frontend app
  - `src/` - React source files
    - `App.jsx`, `main.jsx`, `index.css` - application entry and global styles
    - `api/axios.js` - Axios API client configuration
    - `components/` - shared React components
      - `InputGroup.jsx`, `RequireAuth.jsx`, `SignupWizard.jsx`
    - `pages/` - page-level components
      - `Dashboard.jsx`, `DashboardHome.jsx`, `Login.jsx`, `Signup.jsx`
      - `invoices/` - invoice-related pages
        - `InvoiceCreate.jsx`, `InvoiceList.jsx`, `InvoicePreview.jsx`, `InvoiceView.jsx`
      - `ledger/` - ledger page components
        - `LedgerPage.jsx`
    - `services/` - frontend services and utilities
      - `invoiceCalc.js`
  - `public/` - static assets and HTML template
  - `package.json` - frontend package dependencies and scripts
  - `vite.config.js` - Vite configuration
  - `tailwind.config.js` - Tailwind CSS configuration

- `server/` - Node.js backend server
  - `src/` - server source files
    - `app.js` - Express app setup
    - `config/db.js` - MongoDB connection configuration
    - `controllers/` - request handlers for routes
      - `authController.js`, `invoiceController.js`, `ledgerController.js`, `userController.js`
    - `middlewares/` - middleware functions
      - `authMiddleware.js`
    - `models/` - MongoDB data models
      - `Business.js`, `Invoice.js`, `InvoiceCounter.js`, `Ledger.js`, `User.js`
    - `routes/` - Express route definitions
      - `authRoutes.js`, `invoiceRoutes.js`, `ledgerRoutes.js`, `userRoutes.js`
    - `services/` - backend business services
      - `billingCalculationService.js`, `invoiceNumberService.js`, `invoiceService.js`, `ledgerService.js`
  - `server.js` - backend entry point
  - `package.json` - backend package dependencies and scripts

## Getting Started
1. Install dependencies for both `client` and `server`.
2. Configure environment variables for the server and Firebase Admin.
3. Start the frontend and backend servers.


