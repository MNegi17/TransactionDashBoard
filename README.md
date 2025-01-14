# MERN Stack Project - Product Transactions Dashboard
This project is a full-stack application built using the MERN stack. It integrates backend APIs with a dynamic frontend to display and analyze product transaction data fetched from a third-party API.

##Features
Backend
1. Database Initialization: Fetches data from a third-party API and initializes the database with seed data, supporting efficient collection structures.

2. API for Transactions:
Lists all transactions with support for search and pagination.
Filters transactions by month based on dateOfSale.

3. Statistics API:
Calculates the total sale amount, total sold items, and total unsold items for a selected month.

4. Bar Chart API:
Provides price ranges and the number of items in each range for a selected month.

5. Pie Chart API:
Displays unique categories and the number of items in each category for a selected month.
Unified Data API:
Combines responses from other APIs to provide a consolidated view of transactions, statistics, and chart data.

## Frontend

1. Transactions Table:
Displays transactions with search and pagination functionality.
Includes a dropdown to filter transactions by month (default: March).

2. Statistics Section:
Showcases total sale amount, sold items, and unsold items for the selected month.

3. Charts:
Bar chart visualizes the distribution of products across price ranges.
Pie chart displays the distribution of items across categories.
Technical Highlights

Backend: Node.js, Express.js, MongoDB
Frontend: React.js

Visualization: Charts.js or any preferred charting library
Data Source: Third-Party API
