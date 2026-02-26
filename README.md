# 🛒 E-Commerce Website

A full-stack e-commerce platform built with React frontend and Node.js backend, featuring user authentication, product management, shopping cart, and payment integration.

## 🌐 Deployment

### Live Demo
- **Frontend**: [http://e-commerce-website-rose-pi.vercel.app/)
- **Backend API**: [https://ecommerce-website-3-9ze3.onrender.com](https://ecommerce-website-3-9ze3.onrender.com)

### Vercel Deployment
The project is configured for deployment on Vercel with:
- **Build Command**: `npm run vercel-build`
- **Output Directory**: `public`
- **Start Command**: `npm start`

### Environment Variables for Production
Make sure to set all required environment variables in your deployment platform.
## ✨ Features

### 🛍️ Shopping Experience
- **Product Browsing**: Browse products with search and filtering
- **Shopping Cart**: Add/remove items with quantity management
- **Wishlist**: Save products for later
- **Product Details**: Detailed product information with images

### 👤 User Management
- **User Registration & Login**: JWT-based authentication
- **User Profiles**: Manage personal information
- **Order History**: Track past purchases
- **Address Management**: Save multiple delivery addresses

### 💳 Payment Integration
- **Paytm Integration**: Secure payment processing
- **Order Management**: Complete order lifecycle
- **Payment Status Tracking**: Real-time payment updates

### 🎨 UI/UX Features
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Dark/Light Theme**: Toggle between themes
- **Modern UI**: Material-UI components
- **Smooth Animations**: Enhanced user experience

## 🛠️ Tech Stack

### Frontend
- **React.js** - User interface library
- **Material-UI** - Component library
- **Redux** - State management
- **React Router** - Navigation
- **Axios** - HTTP client

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM for MongoDB
- **JWT** - Authentication
- **Paytm API** - Payment gateway

### Development Tools
- **Git** - Version control
- **npm** - Package manager
- **ESLint** - Code linting
- **Vercel** - Deployment platform

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB Atlas account
- Paytm merchant account (for payments)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Subhajit-Das-1/ECommerce-Website.git
   cd ECommerce-Website
   ```

2. **Install dependencies**
   ```bash
   # Install root dependencies
   npm install
   
   # Install client dependencies
   cd client && npm install
   
   # Install server dependencies
   cd ../server && npm install
   ```

3. **Environment Setup**
   
   Create a `.env` file in the `server` directory:
   ```env
   DB_USERNAME=your_mongodb_username
   DB_PASSWORD=your_mongodb_password
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PAYTM_MERCHANT_KEY=your_paytm_merchant_key
   PAYTM_MID=your_paytm_merchant_id
   PAYTM_WEBSITE=WEBSTAGING
   PAYTM_CHANNEL_ID=WEB
   PAYTM_INDUSTRY_TYPE_ID=Retail
   PAYTM_CUST_ID=CUST_001
   PORT=8000
   NODE_ENV=development
   ```

4. **Run the application**
   ```bash
   # Development mode (runs both client and server)
   npm run dev
   
   # Or run separately:
   # Client (React app)
   cd client && npm start
   
   # Server (Node.js API)
   cd server && npm start
   ```

## 📁 Project Structure

```
ECommerce-Website/
├── client/                 # React frontend
│   ├── public/            # Static files
│   ├── src/
│   │   ├── Components/    # React components
│   │   ├── context/       # React context
│   │   ├── redux/         # Redux store
│   │   ├── service/       # API services
│   │   └── utils/         # Utility functions
│   └── package.json
├── server/                # Node.js backend
│   ├── controller/        # Route controllers
│   ├── database/          # Database connection
│   ├── middleware/        # Custom middleware
│   ├── model/             # Database models
│   ├── routes/            # API routes
│   └── package.json
├── package.json           # Root package.json
└── README.md
```

## 🔧 Available Scripts

### Root Directory
- `npm run dev` - Start both client and server in development
- `npm run install-all` - Install dependencies for both client and server
- `npm run build-all` - Build both client and server
- `npm start` - Start the server

### Client Directory
- `npm start` - Start React development server
- `npm run build` - Build for production
- `npm test` - Run tests

### Server Directory
- `npm start` - Start the server
- `npm run dev` - Start with nodemon (development)

## 🌐 Deployment

### Live Demo
- **Frontend**: [https://e-commerce-website-4939.vercel.app/](https://e-commerce-website-4939.vercel.app/)
- **Backend API**: [https://ecommerce-website-3-9ze3.onrender.com](https://ecommerce-website-3-9ze3.onrender.com)

### Vercel Deployment
The project is configured for deployment on Vercel with:
- **Build Command**: `npm run vercel-build`
- **Output Directory**: `public`
- **Start Command**: `npm start`

### Environment Variables for Production
Make sure to set all required environment variables in your deployment platform.

## 📱 Screenshots

*[Add screenshots of your application here]*

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.


## 🙏 Acknowledgments

- Material-UI for the component library
- MongoDB Atlas for the database service
- Paytm for payment integration
- Vercel for deployment platform

## 📞 Support

If you have any questions or need help, please open an issue on GitHub.

---

⭐ **Star this repository if you found it helpful!**
