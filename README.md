# TaskFlow - Streamlined Task Management System

A modern, attractive task management system built with React, featuring a beautiful login page with multiple authentication options.

## ✨ Features

### 🔐 Authentication
- **Email/Password Login & Signup** - Traditional authentication with form validation
- **Google Sign-in** - One-click authentication with Google
- **Microsoft Sign-in** - Enterprise-ready Microsoft authentication
- **Forgot Password** - Password recovery functionality
- **Form Validation** - Real-time validation with error messages
- **Password Visibility Toggle** - Show/hide password functionality

### 🎨 UI/UX
- **Modern Design** - Glass morphism effects with gradient backgrounds
- **Smooth Animations** - Framer Motion powered animations
- **Responsive Design** - Works perfectly on all devices
- **Interactive Elements** - Hover effects and micro-interactions
- **Loading States** - Beautiful loading animations

### 📱 Dashboard
- **Welcome Screen** - Personalized greeting after login
- **Statistics Cards** - Task completion metrics
- **Quick Actions** - Easy access to common features
- **Logout Functionality** - Secure session management

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd task-management-system
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to see the application

## 🛠️ Tech Stack

- **Frontend Framework**: React 18
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **Font**: Inter (Google Fonts)

## 📁 Project Structure

```
task-management-system/
├── public/
├── src/
│   ├── components/
│   │   ├── LoginPage.jsx      # Main login/signup page
│   │   └── Dashboard.jsx      # Dashboard after login
│   ├── App.jsx               # Main app component with routing
│   ├── main.jsx              # React entry point
│   └── index.css             # Global styles and Tailwind imports
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

## 🎯 Key Components

### LoginPage.jsx
The main authentication component featuring:
- Toggle between login and signup modes
- Social authentication buttons (Google, Microsoft)
- Form validation with error handling
- Password visibility toggle
- Forgot password functionality
- Beautiful glass morphism design
- Smooth animations and transitions

### Dashboard.jsx
A simple dashboard showing:
- Welcome message
- Task statistics
- Quick action buttons
- Logout functionality

## 🎨 Design Features

### Color Scheme
- **Primary**: Blue to Purple gradient
- **Secondary**: Gray tones for text and backgrounds
- **Accent**: White with transparency for glass effects

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

### Animations
- **Page Transitions**: Fade and slide effects
- **Button Interactions**: Scale and hover effects
- **Background Elements**: Floating animations
- **Form Elements**: Smooth transitions

## 🔧 Customization

### Colors
Edit `tailwind.config.js` to customize the color scheme:
```javascript
colors: {
  primary: {
    50: '#eff6ff',
    // ... more shades
  }
}
```

### Animations
Modify animation settings in `tailwind.config.js`:
```javascript
animation: {
  'fade-in': 'fadeIn 0.5s ease-in-out',
  'slide-up': 'slideUp 0.5s ease-out',
}
```

## 📱 Responsive Design

The application is fully responsive and works on:
- **Desktop**: Full feature set with optimal layout
- **Tablet**: Adapted layout with touch-friendly elements
- **Mobile**: Mobile-first design with optimized interactions

## 🔒 Security Features

- **Form Validation**: Client-side validation for all inputs
- **Password Security**: Minimum length requirements
- **Session Management**: Proper logout functionality
- **Input Sanitization**: Protection against XSS attacks

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Lucide React** for beautiful icons
- **Framer Motion** for smooth animations
- **Tailwind CSS** for utility-first styling
- **Inter Font** for modern typography

## 📞 Support

If you have any questions or need help, please open an issue in the repository.

---

**Made with ❤️ for streamlined task management** 