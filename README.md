# Dashboard Zerodha

This is the frontend dashboard interface for the Zerodha clone project.

## Prerequisites

- Node.js installed on your machine.
- A running database instance (e.g., MongoDB, PostgreSQL) required by the backend.

## Step-by-Step Instructions to Run the Project

1. **Clone the repository** (if not already done):
   ```bash
   git clone <repository_url>
   cd dashboard-zerodha
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```
   > **Note**: Packages have been updated to their latest versions.

3. **Initialize Data in Database**:
   Before running the application, ensure your database is initialized with the required dummy data or schemas. Run the database initialization script (typically located in your backend folder):
   ```bash
   # Example: Run your specific database seed/init command
   npm run init-db
   # or for python backends
   # python manage.py migrate && python manage.py loaddata init.json
   ```

4. **Start the Development Server**:
   ```bash
   npm start
   ```
   This runs the app in the development mode.
   Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

## Tech Stack
- React
- Material UI
- Chart.js
