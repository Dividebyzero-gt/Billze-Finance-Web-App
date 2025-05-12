# Banking Application

A modern banking application built with React, TypeScript, and Tailwind CSS. This application provides a comprehensive digital banking experience with features like account management, transfers, bill payments, and more.

## Features

- **User Authentication**: Secure login and registration system
- **Dashboard**: Overview of accounts and recent transactions
- **Account Management**: View and manage multiple accounts
- **Money Transfers**: Transfer funds between accounts
- **Bill Payments**: Pay bills to various service providers
- **Remittance**: Send money internationally
- **Savings & Investments**: Manage savings and investment portfolios
- **Loans & Credit**: Apply for and manage loans
- **User Profile**: Manage personal information
- **Settings**: Customize application preferences
- **Support**: Access help and support resources

## Technology Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **UI Components**: Shadcn UI (Radix UI)
- **State Management**: React Context API
- **Routing**: React Router
- **Backend**: Supabase (Authentication, Database, Storage)
- **Payment Integration**: Flutterwave
- **Charts**: Recharts
- **Form Handling**: React Hook Form with Zod validation

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/banking-application.git
   cd banking-application
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Build for Production

```bash
npm run build
# or
yarn build
```

## Project Structure

```
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── contexts/        # React context providers
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Utility functions and API clients
│   ├── pages/           # Page components
│   ├── types/           # TypeScript type definitions
│   ├── App.tsx          # Main application component
│   └── main.tsx         # Application entry point
├── .gitignore          # Git ignore file
├── index.html          # HTML entry point
├── package.json        # Project dependencies and scripts
├── postcss.config.js   # PostCSS configuration
├── tailwind.config.ts  # Tailwind CSS configuration
├── tsconfig.json       # TypeScript configuration
└── vite.config.ts      # Vite configuration
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn UI](https://ui.shadcn.com/)
- [Supabase](https://supabase.io/)
- [Vite](https://vitejs.dev/)
