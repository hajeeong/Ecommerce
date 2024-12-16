# E-commerce Web Application

## Project Overview  
This project is a modern, full-stack e-commerce web application designed to deliver a seamless and engaging shopping experience. It integrates robust front-end and back-end technologies, ensuring high performance, scalability, and security.  

## Introduction  
The e-commerce application enables users to browse products, add items to a shopping cart, securely make purchases, and manage orders. Admins can manage product listings, orders, and user roles. This project demonstrates the implementation of cutting-edge tools and technologies for a scalable, responsive, and feature-rich platform.

---

## Project Features  
### User Features  
- **User Authentication and Authorization**:  
  - Secure JWT-based authentication for login and registration.  
  - Role-based access control for user and admin functionalities.  
- **Product Management**:  
  - View detailed product pages with images, descriptions, and pricing.  
  - Add, update, and delete products (admin-only feature).  
- **Shopping Cart and Checkout**:  
  - Add, update, or remove products from the cart.  
  - Secure payment processing via **Stripe** integration.  
- **Order Management**:  
  - Track order history and statuses for users.  
  - Admins can manage orders and update statuses.  
- **Image Management**:  
  - Integrated **Cloudinary** for image uploads and optimized storage.  

### Performance and Design  
- **Real-time Updates**:  
  - WebSocket-based real-time updates using **Socket.io**.  
- **Caching**:  
  - Utilized **Redis** to cache frequently accessed data for faster load times.  
- **Responsive Design**:  
  - Fully responsive UI ensuring smooth user experience on any device.  
  - Built with **Tailwind CSS** for customizable and clean design.

---

## Software Tools and Technologies  

### Frontend  
- **React**: Front-end library for building dynamic and interactive UIs.  
- **React Router**: Client-side routing for seamless navigation.  
- **Tailwind CSS**: Utility-first CSS framework for responsive and modern design.  

### Backend  
- **Node.js**: JavaScript runtime for server-side execution.  
- **Express.js**: Minimal, flexible web framework for building APIs.  

### Database  
- **MongoDB**: NoSQL database for storing product, user, and order data.  
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB.  

### Authentication  
- **JWT**: JSON Web Tokens for secure user authentication and session management.  

### Payment Processing  
- **Stripe**: Integrated payment gateway for secure transactions.  

### Image Management  
- **Cloudinary**: Cloud-based image upload, optimization, and management platform.  

### Caching and Real-time  
- **Redis**: In-memory database for caching frequently accessed data.  
- **Socket.io**: Real-time communication for updates and notifications.  

### Build and Development  
- **Vite**: Build tool for fast development and optimized production builds.  

---

## Installation and Setup  

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/hajeeong/Ecommerce.git
   cd Ecommerce
   ```

2. **Install Dependencies**:  
   Navigate to the frontend and backend directories, and run:  
   ```bash
   npm install
   ```

3. **Set Environment Variables**:  
   Create a `.env` file in the `backend` directory with the following variables:  
   ```plaintext
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. **Run the Backend**:  
   ```bash
   cd backend
   npm start
   ```

5. **Run the Frontend**:  
   ```bash
   cd frontend
   npm run dev
   ```

6. **Access the Application**:  
   Open `http://localhost:5173` in your browser.

---

## Screenshots  
![Home Page](link_to_homepage_screenshot)  
![Product Page](link_to_productpage_screenshot)  

---

## Conclusion  
This e-commerce project demonstrates a fully functional, modern, and scalable web application. It highlights the use of industry-standard tools and practices, making it an excellent addition to a professional portfolio. It showcases the seamless integration of a robust tech stack and essential third-party services to deliver a feature-rich and user-friendly platform.
