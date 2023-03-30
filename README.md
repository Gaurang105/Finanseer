
# Finanseer

This project is a responsive, customizable business dashboard web application designed to visualize key performance indicators (KPIs) and other essential metrics for monitoring business performance. The application uses React.js, Material-UI, and Recharts libraries to create an interactive and user-friendly interface.


## Features

- Responsive design: The dashboard is fully responsive and adapts to different screen sizes.
- Customizable components: Reusable components for visualizing various types of data.
- Interactive charts: Interactive line, bar, area, pie, and scatter charts using Recharts library.
- Customizable themes: Theming options using Material-UI.



## Installation

To install the project, follow these steps:

1. Clone the Repository:
```bash
git clone https://github.com/username/Finanseer.git
```
2. Install npm packages for the client:
```bash
npm i react-redux @reduxjs/toolkit react-router-dom @mui/material @emotion/react @emotion/styled @mui/icons-material @mui/x-data-grid
```
3. ```bash
    npm i -D @types/react-dom
   ```

4. ```bash
    npm i -D eslint eslint-config-react-app
   ```

5. Start the Front-end Development(client) Server:
```bash
npm run dev
```
6. Start the Back-end Development(server) Server:
```bash
npm run dev
```

The application should now be running at http://localhost:5173/
## Website Front-End Implementation

### Tools Used
- React
- Material-UI
- Vite
- Recharts
- Redux
- Typescript

### Web-Page Design
The application consists of a dashboard with multiple components, each displaying specific KPIs and business metrics. The dashboard is designed with a grid layout to ensure responsiveness and adaptability across different devices and screen sizes.
The components are organized into three rows.
The web page design consists of a responsive dashboard that displays the historical revenue data, a linear regression model, and predicted revenue for the next year. The application includes:

- A Material-UI AppBar component displaying the application title.
- A line chart created with Recharts, displaying historical revenue, expenses, and profit data.
- A table displaying detailed monthly and daily data.
- A button to toggle the visibility of the predicted revenue data.



## Screenshots

![Dashboard](https://github.com/Gaurang105/Finanseer/blob/master/images/dash.png?raw=true)

![Predictions](https://github.com/Gaurang105/Finanseer/blob/master/images/ml.png?raw=true)

## Website Backend Implementation

### Tools Used
- Node.js
- Express
- Mongoose
- Helmet
- Morgan
- CORS
- dotenv

### Code for backend
The backend code includes RESTful API endpoints for fetching data related to KPIs, products, and transactions. It connects to the MongoDB database using Mongoose and follows best practices for code organization and structure.

## Database Design

### Database used
The application uses MongoDB, a popular NoSQL document-based database, for storing data.

### Database schema and Tables used
The database has three collections: KPI, Product, and Transaction. The schemas for these collections are defined using Mongoose.

- The KPI schema stores the total profit, revenue, expenses, and monthly and daily data.
- The Product schema contains information about the products, including their name, price, and description.
- The Transaction schema stores transactional data such as date, revenue, and expenses.## Screenshots

![Database Architecture](https://github.com/Gaurang105/Finanseer/blob/master/images/db.architecture.png?raw=true)

![Kpis](https://github.com/Gaurang105/Finanseer/blob/master/images/db.kpis.png?raw=true)

![Products](https://github.com/Gaurang105/Finanseer/blob/master/images/db.products.png?raw=true)

![Transactions](https://github.com/Gaurang105/Finanseer/blob/master/images/db.transactions.png?raw=true)
## Acknowledgements

 - [React](https://react.dev/)
 - [Material-UI](https://mui.com/core/)
 - [Vite](https://vitejs.dev/)
 - [Recharts](https://recharts.org/en-US/)
 - [Node.js](https://nodejs.org/en)
 - [Express](https://expressjs.com/)
 - [Mongoose](https://mongoosejs.com/)
 - [MongoDB](https://www.mongodb.com/)


## Future Developments

Planned improvements and expansions for this project include:

- Integration of additional data sources, such as social media engagement, website traffic, and customer feedback.
- Implementation of advanced data analysis techniques, such as machine learning and artificial intelligence.
- Development of a user management system for multi-user access and personalized views.
- Additional customization options, such as chart type selection and user-defined KPIs.
- Expansion of the backend functionality for third-party integrations and data sharing.
## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to provide a detailed description of the changes and include any relevant issue numbers.
## License

This project is licensed under the MIT License. See the [License](https://choosealicense.com/licenses/mit/) file for more information.

