# Turtles All The Way Down

A centralized platform for presenting verified facts on vaccine safety and efficacy, inspired by *Turtles All The Way Down: Vaccine Science and Myth*. The app includes a reference library, counterpoints, interactive visualizations, moderated discussions, and supports web and Electron-based desktop apps.

## Project Structure
- : Go backend with Gin and /GORM.
- : React.js frontend with TypeScript and Vite.
- : Electron app for Windows/macOS, reusing the React frontend.

## Setup Instructions
### Prerequisites
- Go (v1.21 or later)
- Node.js (v18 or later)
- Git
- AWS CLI (for deployment, optional initially)

### Clone Repository


### Backend Setup

- Server runs at .

### Frontend Setup

- Vite server runs at .

### Electron Setup

- Ensure the frontend Vite server is running.

## Next Steps
- Configure AWS credentials for KMS and S3.
- Set up PostgreSQL locally or via AWS RDS.
- Implement  for database queries.

## License
MIT License
