# Restaurant Management System (RMS)

A comprehensive web application for restaurant management built with modern web technologies. This system allows restaurant owners to manage their menu, orders, and customer authentication.

## 🍽️ About the Project

The Restaurant Management System is designed to streamline restaurant operations by providing an intuitive interface for both customers and restaurant staff. Customers can browse the menu, place orders, and create accounts, while restaurant staff can manage the menu items, track orders, and showcase their chefs.

## 🚀 Technologies Used

- **Frontend**:
  - React.js (v18.1.0)
  - React Router DOM (v5.3.4) for navigation
  - React Redux & Redux Toolkit for state management
  - Styled Components for styling
  - React Icons for UI icons

- **Backend & Database**:
  - Firebase Realtime Database for storing menu items and other data
  - Firebase Authentication for user authentication
  - Firebase Hosting for deployment

## ✨ Key Features

- **User Authentication**: Secure login and signup functionality using Firebase Authentication
- **Menu Management**: Display and manage menu items fetched from Firebase Realtime Database
- **Shopping Cart**: Add items to cart, modify quantities, and place orders
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Chef Profiles**: Showcase the restaurant's chefs and their specialties
- **About Us Page**: Information about the restaurant and its values

## 🛠️ Project Structure

- `src/components`: UI components organized by feature
  - `Auth`: Authentication components
  - `OrderComp`: Order-related components including cart and meals
  - `HomeComp`: Homepage components
  - `chefComp`: Chef profile components
  - `AboutComp`: About page components
- `src/pages`: Main application pages
- `src/store`: Context providers and state management
- `src/Global`: Global components like header and footer
- `src/pictures`: Image assets

## 🔐 Authentication

The application uses Firebase Authentication with email/password method. Users can:
- Create a new account
- Login with existing credentials
- Access protected routes only when authenticated
- Auto-logout when the token expires

## 🛒 Order System

The ordering system allows users to:
- Browse available menu items
- Add items to cart
- Adjust quantities in the cart
- View the total order amount
- Place orders

## 🚀 Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Restaurant-Management-system.git
   ```

2. Navigate to the project directory:
   ```
   cd Restaurant-Management-system
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## 🔥 Deployment

The application is configured for deployment on Firebase Hosting. To deploy:

1. Build the project:
   ```
   npm run build
   ```

2. Deploy to Firebase:
   ```
   firebase deploy
   ```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
