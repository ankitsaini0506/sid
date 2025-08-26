# WPLCHMY.AI: Restaurant Self-Ordering System

A modern restaurant self-ordering system with QR integration, built with React Native and Expo.

## Features

- 📱 **Menu Display**: Browse restaurant menu with categories
- 🛒 **Shopping Cart**: Add items and manage quantities
- 💳 **Payment Integration**: Multiple payment methods (Razorpay, UPI, QR)
- 👨‍💼 **Admin Dashboard**: Real-time order management
- 📊 **Order Tracking**: Live order status updates
- 🔔 **Notifications**: Real-time order notifications
- 📱 **QR Integration**: QR code generation and scanning

## Tech Stack

- **Frontend**: React Native, Expo
- **State Management**: Zustand
- **Database**: Firebase Realtime Database
- **Styling**: NativeWind (Tailwind CSS)
- **Icons**: Lucide React Native
- **QR Codes**: react-native-qrcode-svg

## Deployment

### Netlify Deployment

This project is configured for easy deployment on Netlify.

#### Automatic Deployment

1. **Connect to GitHub**: Link your GitHub repository to Netlify
2. **Build Settings**:
   - Build command: `npm run build:web`
   - Publish directory: `web-build`
   - Node version: `18`

#### Manual Deployment

1. **Build the project**:
   ```bash
   npm run build:web
   ```

2. **Deploy to Netlify**:
   - Drag and drop the `web-build` folder to Netlify
   - Or use Netlify CLI: `netlify deploy --prod --dir=web-build`

## Local Development

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start development server**:
   ```bash
   npm start
   ```

3. **Run on web**:
   ```bash
   npm run start-web
   ```

## Environment Variables

Create a `.env` file with your Firebase configuration:

```env
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_auth_domain
FIREBASE_DATABASE_URL=your_database_url
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
FIREBASE_APP_ID=your_app_id
```

## Admin Access

- **Username**: `admin`
- **Password**: `admin123`

## License

MIT License 