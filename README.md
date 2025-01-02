
# Stock Market Simulation and Tracking Application

This project is a web-based stock market simulation and tracking application built using Flask and various supporting Python libraries. It allows users to register, login, and simulate stock market operations, including buying, selling, and tracking stocks in real-time.

## Features

- **User Authentication**: Register, login, and logout functionality with password hashing for secure authentication.
- **Real-Time Stock Data**: Fetch live stock prices and performance metrics from NSE (National Stock Exchange) using the `jugaad_data` library.
- **Portfolio Management**: 
  - Track current stocks, stock purchases, and sales.
  - Monitor portfolio balance and state changes.
- **Graphical Visualization**: 
  - Interactive stock performance graphs using the Bokeh library.
  - Support for multiple time ranges (1 Week, 1 Month, 1 Year, 5 Years) and data types (Closing Price, Volume, etc.).
- **Watchlist**: Add stocks to a personal watchlist for quick tracking.
- **Dynamic Updates**: Update graphs, performance, and watchlist dynamically.

## Technology Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, Bokeh (for graphs)
- **Database**: SQLite (using SQLAlchemy ORM)
- **Libraries Used**:
  - `jugaad_data.nse` for live stock market data.
  - `Werkzeug` for secure password hashing.
  - `Bokeh` for graphical visualizations.

## Folder Structure

```
project-directory/
├── templates/             # HTML templates for Flask routes
├── static/                # Static files (CSS, JS, images)
├── app.py                 # Main Flask application
└── README.md              # Project documentation
```

## Acknowledgments

- Thanks to the `jugaad_data` library for providing stock market data.
- Inspired by the need to simulate and understand stock market operations.
