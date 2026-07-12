# e-plantShopping: Paradise Nursery
Small plants online shop with basic featuress: users can browse a list of houseplants and add them to a shopping cart with quantity adjustment.

# Features
* Browse products (static data in ProductList.jsx)
* Add to cart, remove, increment/decrement (CartSlice.jsx + Redux Toolkit)
* View total cost & individual subtotals
* Landing page with hero background (App.css) and “Get Started” button (App.jsx)
* About Us component (AboutUs.jsx)

# Tech Stack
React 18+
Redux Toolkit & react‑redux
Plain CSS (App.css)
# Folder Structure and main files
```
├─ src/
│ └─ App.css
│ ├─ AboutUs.jsx       #details about the company
│ ├─ App.jsx           #landing page with the company name and a **"Get Started"** button
│ ├─ CartItem.jsx
│ ├─ CartSlice.jsx     #Redux slice for the shopping cart
│ └─ ProductList.jsx
│ ├─ store.js
```
# Install & Run
## Clone repo
```sh
git clone <repo-url>
cd e-plantShopping
```

## Install deps
```sh
npm install   # or yarn
```

## Start dev server
```sh
npm run dev   # (Vite) or npm start (CRA)
```

## Usage
Open http://localhost:5173 (or 3000). Click “Get Started” to view products. Add items to cart, adjust quantities, and review total before checkout.