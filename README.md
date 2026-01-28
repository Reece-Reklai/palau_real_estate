# Palau Real Estate

A web application for browsing real estate listings in Palau with user authentication and contact features.

## Features

- **User Authentication**: Register and login through Google Firebase Authentication
- **Property Listings**: View house listings for sale with data from Firebase
- **Weather Information**: Current weather for Palau implemented using web scraping
- **Contact Service**: Contact the team through EmailJS email service

## Technologies Used

- Firebase (Authentication & Database)
- EmailJS
- Web Scraping for weather data

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn
- Firebase project
- EmailJS account

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd palau_real_estate
   ```

2. Navigate to the React app directory:
   ```bash
   cd reactApp
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Environment Setup

1. Create a `.env` file in the `reactApp` directory with your Firebase and EmailJS configuration:
   ```env
   REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   REACT_APP_EMAILJS_SERVICE_ID=your_emailjs_service_id
   REACT_APP_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
   REACT_APP_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
   ```

### Running the Application

1. Start the development server:
   ```bash
   npm start
   ```

2. Open your browser and navigate to `http://localhost:3000`

### Building for Production

To create a production build:
```bash
npm run build
```
