# 🛒 BazaarHub - Full-Stack Marketplace

A complete, production-ready marketplace web application with React + TypeScript frontend and mock backend using localStorage for demo purposes.

## 🌟 Features

### Buyer Features
- 🛍️ Browse products with categories
- 🔍 Search and filter products
- 🛒 Shopping cart functionality
- 💳 Checkout with UPI payment simulation
- 📦 Order tracking and history

### Seller Features
- 📝 Seller registration with OTP verification
- 📊 Seller dashboard with analytics
- ➕ Add, edit, delete products
- 💰 Earnings tracking (90% after 10% commission)
- 📋 View orders

### Admin Features
- 🔐 Secure admin access (Password: `rishabh1745T`)
- 👥 Seller management (approve, reject, block)
- 📦 Product management (edit, delete any product)
- 💳 Order verification and payment approval
- 📢 Ad management
- 📊 Statistics dashboard

### Special Features
- 🏆 Buyer leaderboard
- 📢 Advertisement system
- 🚚 Delivery cost calculation
- 📱 Fully responsive design
- ✨ Beautiful gradient UI

## 🚀 Tech Stack

- **Frontend**: React 19 + TypeScript + Vite
- **Styling**: Tailwind CSS 4
- **State**: React Context API
- **Icons**: Lucide React
- **Notifications**: React Hot Toast
- **Storage**: LocalStorage (simulates backend)

## 📁 Project Structure

```
src/
├── components/        # Reusable UI components
│   ├── Navbar.tsx
│   ├── Footer.tsx
│   └── ProductCard.tsx
├── context/           # React Context providers
│   ├── AuthContext.tsx
│   └── CartContext.tsx
├── pages/             # Page components
│   ├── Home.tsx
│   ├── Products.tsx
│   ├── ProductDetail.tsx
│   ├── Cart.tsx
│   ├── Checkout.tsx
│   ├── Login.tsx
│   ├── Register.tsx
│   ├── Orders.tsx
│   ├── SellerDashboard.tsx
│   └── AdminPanel.tsx
├── services/          # API and data services
│   ├── api.ts
│   └── mockData.ts
├── App.tsx            # Main app with routing
├── main.tsx           # Entry point
└── index.css          # Global styles
```

## 🛠️ Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to project
cd bazaarhub

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

### Environment Variables

Create a `.env` file (optional):

```env
# API URL (for future backend integration)
VITE_API_URL=http://localhost:5000/api
```

## 🔐 Admin Access

### Method 1: Via Footer Button
1. Scroll to the footer
2. Click "Admin Portal" button
3. Enter the secret key

### Method 2: Via Login Page
1. Use demo credentials:
   - Phone: `9999999999`
   - Password: `rishabh1745T`

## 💳 Payment Flow

1. Buyer adds items to cart
2. Proceeds to checkout
3. Enters delivery address
4. Pays via UPI to: `8595784629@fam`
5. Enters UTR number and uploads screenshot
6. Admin verifies payment
7. Order status updates to "verified"

## 📦 Order Status Flow

```
processing → verified → shipped → delivered
```

## 🚀 Deployment

### Frontend (Netlify)

1. Build the project:
```bash
npm run build
```

2. Deploy the `dist` folder to Netlify

### Backend (For Future Integration)

```bash
# Create server directory
mkdir server && cd server

# Initialize Node.js project
npm init -y

# Install dependencies
npm install express mongoose cors dotenv

# Create server.js with MongoDB connection
```

## 📱 Responsive Design

- Mobile-first approach
- Tablet and desktop optimized
- Smooth animations and transitions

## 🎨 UI Features

- 🌈 Gradient backgrounds
- ✨ Glass morphism effects
- 🎯 Hover animations
- 📸 Image zoom on hover
- 🔔 Toast notifications
- ⏳ Loading states

## 📝 Demo Data

The app comes with:
- 8 sample products
- 2 sample advertisements
- Sample orders for testing
- Pre-configured admin account

## 🔧 Future Enhancements

- [ ] Real backend with Node.js + MongoDB
- [ ] JWT authentication
- [ ] Real OTP via SMS API
- [ ] Image upload to cloud storage
- [ ] Email notifications
- [ ] Advanced analytics
- [ ] Multi-language support

## 📄 License

MIT License - feel free to use this project for your needs!

---

Made with ❤️ by BazaarHub Team
