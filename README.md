

# Shopmate: Context & Reducers Implementation 🛍️

## Overview 🛒
**Shopmate** is an enhanced e-commerce shopping cart application built using **React Context API & Reducers** for state management. Users can browse products, add/remove them from the cart, and view their total dynamically.

## Features ✨
- **Global State Management**: Uses React Context API and Reducers.
- **Product Listing**: Displays dynamic products.
- **Cart Functionality**: Add or remove items from the cart.
- **Total Calculation**: Automatically updates cart total.
- **Persistent Page Titles**: Dynamically updates document titles.
- **Navigation**: Smooth transitions with React Router.
- **Footer Section**: Includes quick links and contact details.
- **Mobile Responsive**: Clean, adaptable UI for all devices.

## Built With 🛠️
### Technologies Used:
- React.js ⚛️
- React Router 🚏
- Context API & Reducers 🎛️
- JavaScript (ES6+)
- CSS3 🎨

### Tools & Libraries:
- **State Management**: React Context API + Reducers
- **Routing**: React Router DOM
- **Version Control**: Git & GitHub

## Installation 💻
### 1️⃣ Clone the Repository:
```bash
$ git clone https://github.com/UrstrulyBhavana/Shopmate.git
$ cd Shopmate
```

### 2️⃣ Install Dependencies:
```bash
$ npm install
```

### 3️⃣ Start the Development Server:
```bash
$ npm start
```

### 4️⃣ Build for Production:
```bash
$ npm run build
```

## Folder Structure 📂
```
Shopmate
├── src
│   ├── components
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── CartCard.js
│   │   ├── ProductCard.js
│   ├── context
│   │   ├── CartContext.js
│   ├── hooks
│   │   ├── useTitle.js
│   ├── pages
│   │   ├── Home.js
│   │   ├── Cart.js
│   ├── reducer
│   │   ├── cartReducer.js
│   ├── routes
│   │   ├── AllRoutes.js
│   ├── assets (Images & logos)
│   ├── styles (CSS files)
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   ├── index.css
│   ├── package.json
│   ├── README.md
```

## Functionalities 🚀
1. **Global State Management**:
   - Uses **React Context API & Reducers** for cart state.
   - `CartContext.js` handles state logic.

2. **Product Listings**:
   - Displays products dynamically with images, names, and prices.
   - Uses **ProductCard** component for modularity.

3. **Cart Functionality**:
   - Users can **add/remove** items from the cart.
   - Cart total updates dynamically.
   - Uses `cartReducer.js` for efficient state updates.

4. **Footer Section**:
   - Contains quick links to Home, Cart, GitHub Repo, and Live Demo.
   - Displays contact details including email, GitHub, and LinkedIn.
   - Styled with **Footer.css**.

5. **Navigation & Routing**:
   - React Router for seamless navigation.
   - Active navigation links with cart count display.

6. **Custom Hooks**:
   - `useTitle.js` dynamically updates page titles.

7. **Responsive Design**:
   - Styled with CSS for a clean, mobile-friendly layout.

## Demo.gif 🌟

## Contributing 🤝
We welcome contributions! 🚀 If you’d like to contribute:
1. **Fork** this repository.
2. Create a **new branch** (`feature/new-feature`).
3. **Commit** your changes.
4. **Push** to your fork.
5. Open a **Pull Request**.

## Contact 📧
- **Developer**: Linga Bhavana
- **GitHub**: [UrstrulyBhavana](https://github.com/UrstrulyBhavana)
- **Email**: urstrulybhavana1432@gmail.com

## License 📄
This project is licensed under the **MIT License**.

