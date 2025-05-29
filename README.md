# QORE - Smart-Powered Recruitment Engine

QORE is a comprehensive recruitment platform featuring both backend API and frontend interface for managing the entire recruitment process.

## Project Structure

- **QORE Backend/** - Node.js/Express backend API
- **QORE Frontend/** - React/TypeScript frontend application

## Backend Features

- User authentication and authorization
- Role-based access control (RBAC)
- Employee management
- Job management
- Interview scheduling
- Resume parsing
- Email and SMS notifications

## Frontend Features

- Modern React application with TypeScript
- Responsive UI with Tailwind CSS
- Role and permission management
- Employee profiles and teams
- Job posting and management
- Resume upload and analysis
- Interview scheduling
- Reports and analytics

## Getting Started

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd "QORE Backend"
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables (create .env file)

4. Run database migrations:
   ```bash
   npm run db:migrate
   ```

5. Seed the database:
   ```bash
   npm run db:seed
   ```

6. Start the server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd "QORE Frontend"
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## Technologies Used

### Backend
- Node.js
- Express.js
- Sequelize ORM
- PostgreSQL/MySQL
- JWT Authentication
- bcrypt for password hashing
- Firebase Admin SDK

### Frontend
- React 18
- TypeScript
- Vite
- Tailwind CSS
- Radix UI components
- React Query (TanStack Query)
- React Hook Form
- Axios for API calls

## API Documentation

Detailed API documentation is available in the `QORE Backend/docs/` directory.

## Contributing

Please read the contribution guidelines before submitting pull requests.

## License

This project is licensed under the ISC License.