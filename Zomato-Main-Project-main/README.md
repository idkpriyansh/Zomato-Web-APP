# Zomato-Main-Project


This is a web application built using React, MongoDB, AWS for cloud storage, and Google Authentication. It provides a platform for users to explore restaurants, view menus, and place orders.


## Features

- User authentication using Google OAuth 2.0
- Browse and search for restaurants
- View restaurant details, including menu items and reviews
- Place orders and track order status
- Cloud storage for images and other assets using AWS S3
- Interactive user interface for a seamless browsing experience

## Technologies Used

- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Cloud Storage**: AWS S3
- **Authentication**: Google OAuth 2.0

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/zomato-website.git
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd zomato-website
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the `backend` directory and set the following variables:
     ```
     MONGODB_URI=<your-mongodb-uri>
     GOOGLE_CLIENT_ID=<your-google-client-id>
     AWS_ACCESS_KEY=<your-aws-access-key>
     AWS_SECRET_KEY=<your-aws-secret-key>
     AWS_REGION=<your-aws-region>
     AWS_BUCKET_NAME=<your-aws-bucket-name>
     ```

4. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

5. Start the frontend development server:
   ```bash
   cd frontend
   npm start
   ```

6. Access the application in your web browser at `http://localhost:3000`.

## Usage

- Visit the homepage and use Google Authentication to log in.
- Browse the list of restaurants, view their menus, and read reviews.
- Place orders for your favorite dishes and track their status.
- Enjoy a smooth user experience with interactive features.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


Feel free to customize this template according to your project's specifics. The README should provide enough information for other developers to understand, install, and use your application.npm start

Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.
npm test

Launches the test runner in the interactive watch mode.
See the section about running tests for more information.
npm run build

Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.
npm run eject

Note: this is a one-way operation. Once you eject, you can’t go back!

If you aren’t satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
