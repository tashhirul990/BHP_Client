# Bengaluru House Price Prediction App

This is a React-based frontend application for predicting house prices in Bengaluru. The app allows users to input details such as the size of the home, number of bedrooms, bathrooms, and location to get an estimated price.

## Live Demo

You can access the live hosted version of the app here: [Bengaluru House Price Prediction App](https://bhp-client-c8td.onrender.com/)

## Features

- Fetches location data dynamically from the backend.
- Allows users to input home details (size, bedrooms, bathrooms, location).
- Displays the predicted price based on user input.
- Clear form functionality to reset inputs.

## Technologies Used

- React
- Tailwind CSS
- Axios for API requests

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/bhp-client.git
   cd bhp-client
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

   The app will be available at [http://localhost:3000](http://localhost:3000).

## Folder Structure

```
bhp-client/
├── public/             # Static files
├── src/                # Source code
│   ├── App.js          # Main application component
│   ├── index.js        # Entry point
│   ├── App.css         # Styling for the app
│   ├── index.css       # Global styles
│   └── ...             # Other files
├── package.json        # Project configuration
└── README.md           # Project documentation
```

## API Endpoints

The app communicates with the backend via the following endpoints:

- **GET /get_locations**: Fetches the list of available locations.
- **POST /predict_home_price**: Predicts the house price based on user input.

## Deployment

This app is deployed using [Render](https://render.com/). The live version is available at [https://bhp-client-c8td.onrender.com/](https://bhp-client-c8td.onrender.com/).

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [Create React App](https://github.com/facebook/create-react-app)
- [Tailwind CSS](https://tailwindcss.com/)
- [Render](https://render.com/)
