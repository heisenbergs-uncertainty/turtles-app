# Turtles All The Way Down

A centralized platform for presenting verified facts on vaccine safety and efficacy, inspired by _Turtles All The Way Down: Vaccine Science and Myth_. The app includes a reference library, counterpoints, interactive visualizations, moderated discussions, and supports web and Electron-based desktop apps.

## Project Structure

- `/backend`: Go backend with Gin and `gen`/GORM.
- `/frontend`: React.js frontend with TypeScript and Vite.
- `/electron`: Electron app for Windows/macOS, reusing the React frontend.

## Setup Instructions

### Prerequisites

- Go (v1.21 or later)
- Node.js (v18 or later)
- Git
- AWS CLI (for deployment, optional initially)

### Clone Repository

`bash
git clone https://github.com/<your-username>/turtles-app.git
cd turtles-app
`

### Backend Setup

`bash
cd backend
go mod tidy
go run main.go
`

- Server runs at `http://localhost:8080`.

### Frontend Setup

`bash
cd frontend
npm install
npm run dev
`

- Vite server runs at `http://localhost:5173`.

### Electron Setup

`bash
cd electron
npm install
npm start
`

- Ensure the frontend Vite server is running.

## Next Steps

- Configure AWS credentials for KMS and S3.
- Set up PostgreSQL locally or via AWS RDS.
- Implement `gen` for database queries.

## License

MIT License
