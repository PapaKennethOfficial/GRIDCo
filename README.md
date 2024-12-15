# GRIDCo
 Development code for the GRIDCo field trip report

# Gridco Monitoring System

This is a simple web application built using Flask for monitoring the grid data, user incidents, and system analytics for the Gridco platform. The application allows users to register, log in, and view important system data and analytics.

## Features

- **User Registration and Login**: Users can register an account, log in, and access the dashboard.
- **Dashboard**: Displays the latest grid data (voltage, current, frequency) in real-time.
- **Incidents**: Users can submit and view incidents related to the system.
- **Analytics**: Displays average voltage, current, and frequency over time.
- **Cybersecurity Logs**: Displays basic security log entries (this feature can be expanded as needed).
- **Grid Data API**: Allows external systems to post grid data via the `/api/grid-data` endpoint.

## Requirements

To run this application locally, ensure you have the following installed:

- Python 3.x
- Flask
- MySQL
- MySQL connector for Python

You can install the required Python dependencies using `pip`:
pip install flask mysql-connector

## Setup
Clone the repository:

git clone <repository-url>
cd <repository-directory>

Run the application:
python app.py
