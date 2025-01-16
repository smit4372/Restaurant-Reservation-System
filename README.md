# Restaurant Reservation System

## Overview
The **Restaurant Reservation System** is a comprehensive web application designed to enhance the dining experience for both customers and restaurant administrators. Customers can order food online, reserve tables, leave reviews, and access their bills conveniently. On the other hand, administrators can manage restaurant details, update menu items, adjust operating hours, and manage table configurations.

This project was developed as part of an academic assignment using **React** for the frontend and **PostgreSQL** for the backend. It is hosted on **Neon**.

## Features

### Customer Features
* **Online Orders**: Place orders from the menu.
* **Table Reservations**: Book tables in advance.
* **Reviews**: Leave feedback about your dining experience.
* **Billing**: Receive bills online for convenience.
* **Order Ahead**: Schedule your orders to be ready when you arrive.

### Admin Features
* **Restaurant Management**: Add or update restaurant details, such as hours and number of tables.
* **Menu Management**: Add, update, or remove menu items.
* **Table Configuration**: Set the number of tables and seats.
* **Operational Management**: Adjust operational details as needed.

## Technologies Used
* **Frontend**: React
* **Backend**: Node.js with PostgreSQL
* **Hosting**: Neon

## Getting Started

### Prerequisites
* **Node.js** (latest version recommended)
* **npm** (comes with Node.js)
* A PostgreSQL database setup

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/restaurant-reservation-system.git
```

2. Navigate to the project directory:
```bash
cd restaurant-reservation-system
```

3. Install dependencies:
```bash
npm install
```

### Running the Application

1. Open the terminal and split it into two panes.

2. **Start the Backend**:
   * In one terminal pane, run:
   ```bash
   node src/server/server.js
   ```
   * You should see: `Server running on port 3000`

3. **Start the Frontend**:
   * In the second terminal pane, run:
   ```bash
   npm run dev
   ```
   * Copy the highlighted link (e.g., `http://localhost:5173/`) and paste it into your browser.

4. Sign in with any email to explore the application.

## Project Structure
```
restaurant-reservation-system/
├── src/
│   ├── components/   # React components
│   ├── server/       # Backend server files
│   ├── assets/       # Static assets
│   └── utils/        # Utility functions
├── public/           # Public files
├── package.json      # Node.js dependencies
└── README.md         # Project documentation
```

## Video Demonstration
A video walkthrough of the project is available in the repository.

## Academic Integrity
This project was created as part of an academic assignment. Any unauthorized copying, sharing, or use for cheating purposes is strictly prohibited. Please respect academic integrity.

## Contributors
* **Your Name** - Developer and project contributor
* **Friend's Name** - Developer and project contributor

## Future Enhancements
* Integrate payment gateways for secure transactions
* Implement advanced analytics for administrators
* Add multi-language support for broader accessibility

## License
This project is licensed under the MIT License.

Feel free to reach out for any queries or feedback about the project!
