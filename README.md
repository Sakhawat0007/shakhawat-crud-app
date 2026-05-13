# 🚀 Shakhawat CRUD App

**React Firebase Firestore Single Page Application with Tailwind CSS**

## 📋 Overview

A fully functional CRUD (Create, Read, Update, Delete) application built with:
- ⚛️ **React 18** - UI Library
- 🔄 **React Router DOM v6** - SPA Navigation  
- 🔥 **Firebase Firestore** - NoSQL Database
- 🎨 **Tailwind CSS** - Modern Styling

## ✨ Features

### 🏠 Routes
- `/` - Home page with feature overview
- `/create` - Create new items form
- `/items` - View all items in card layout
- `/item/:id` - Dynamic route for single item details
- `/edit/:id` - Edit existing item

### ✅ CRUD Operations
- **Create** - Add new items with title, description, and category
- **Read** - Fetch and display all items from Firestore
- **Read (Single)** - View detailed information of a single item
- **Update** - Edit existing items with pre-filled form fields
- **Delete** - Remove items with confirmation dialog

### 🎨 UI/UX Features
- Responsive design (mobile, tablet, desktop)
- Gradient backgrounds and smooth animations
- Loading states and error handling
- Form validation
- Empty state messaging
- Confirmation dialogs for critical actions
- SPA navigation without page reloads

## 📁 Project Structure

```
shakhawat-crud-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── Navbar.js
│   ├── config/
│   │   └── firebase.js
│   ├── pages/
│   │   ├── Home.js
│   │   ├── CreateItem.js
│   │   ├── ViewAllItems.js
│   │   ├── ViewSingleItem.js
│   │   └── EditItem.js
│   ├── App.js
│   ├── index.js
│   └── index.css
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── firebase.json
├── .firebaserc
└── README.md
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Firebase account

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Sakhawat0007/shakhawat-crud-app.git
cd shakhawat-crud-app
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm start
```
The app will open at `http://localhost:3000`

## 🌐 Deployment

### Deploy to Firebase Hosting

1. **Install Firebase CLI**
```bash
npm install -g firebase-tools
```

2. **Login to Firebase**
```bash
firebase login
```

3. **Build for production**
```bash
npm run build
```

4. **Deploy**
```bash
firebase deploy
```

Your app will be live at: `https://web-shakhawat.firebaseapp.com`

## 🔧 Available Scripts

- `npm start` - Run development server
- `npm run build` - Build for production
- `npm test` - Run tests
- `firebase deploy` - Deploy to Firebase Hosting

## 📸 Routes & Pages

### Home Page (`/`)
- Hero section with app overview
- Feature cards (Create, Read, Update, Delete)
- Tech stack display

### Create Item Page (`/create`)
- Form with title, description, and category
- Form validation
- Loading state on submission

### View All Items Page (`/items`)
- Responsive card grid layout
- View, Edit, Delete buttons for each item
- Empty state messaging

### Single Item Page (`/item/:id`) - Dynamic Route
- Full item details
- Item information section
- Edit and Delete buttons

### Edit Item Page (`/edit/:id`)
- Pre-filled form with existing data
- Update functionality
- Cancel option

## ✅ Assignment Requirements Met

✅ Task 1: SPA Routing with React Router DOM
✅ Task 2: Full CRUD with Firebase Firestore
✅ Task 3: Deploy on Firebase Hosting
✅ Task 4: GitHub Repository with proper structure

---

**Live URL:** https://web-shakhawat.firebaseapp.com
**GitHub Repository:** https://github.com/Sakhawat0007/shakhawat-crud-app
