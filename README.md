# FoodBridge for Hunger

FoodBridge for Hunger is a web-based food donation platform designed to connect food donors, NGOs, and administrators through a simple and efficient workflow. The project aims to reduce food waste and improve food accessibility by enabling donors to post surplus food, NGOs to browse nearby donations, and authorized users to manage donation requests.

## Project Overview

The application is divided into two main parts:

- **Frontend**: A responsive user interface built with HTML, CSS, and vanilla JavaScript.
- **Backend**: A RESTful API built with Node.js and Express, secured with JWT-based authentication.

This project demonstrates a lightweight full-stack architecture suitable for academic submissions, prototypes, and community-focused social impact solutions.

## Key Features

- Secure login using JSON Web Tokens (JWT)
- Role-based demo access for Donor, NGO, and Admin
- Post new food donations with quantity, expiry date, and geo-location
- Browse all available donations
- Filter donations by latitude, longitude, and search radius
- Submit requests against specific donation listings
- View request activity in the dashboard
- Clean dashboard UI with overview statistics and recent donation tracking

## Tech Stack

### Frontend
- HTML5
- CSS3
- Vanilla JavaScript

### Backend
- Node.js
- Express.js
- CORS
- JSON Web Token (`jsonwebtoken`)
- `bcryptjs`

## Project Structure

```text
FoodBridge_for_Hunger/
├── food-donation-app/
│   ├── frontend/
│   │   ├── index.html
│   │   ├── app.js
│   │   └── style.css
│   └── backend/
│       ├── server.js
│       ├── package.json
│       ├── routes/
│       │   ├── auth.js
│       │   ├── donations.js
│       │   └── requests.js
├── Outputs/
│   └── *.jpg
└── package-lock.json
