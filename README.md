

# Book Store

## Project Structure
The project is organized as follows:
```
├── build
│   ├── static
│   │   ├── css
│   │   ├── js
│   │   └── media
│   ├── _redirects
│   ├── asset-manifest.json
│   ├── favicon-icon.png
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── public
│   ├── _redirects
│   ├── favicon-icon.png
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src
├── package-lock.json
├── package.json
└── README.md
```

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd book-store
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application
1. Start the development server:
   ```bash
   npm start
   ```
2. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

The page will reload automatically when changes are made, and lint errors will appear in the console.

## Usage
- The application provides features such as user authentication, product filtering, wishlist and cart management, and order summaries.
- Razorpay is integrated for secure payment processing.

## Technologies Used
1. **Frontend**:
   - HTML
   - CSS
   - JavaScript
   - React
2. **Backend**:
   - Node.js
   - Express.js
   - MongoDB (Deployed on Vercel)

## Features
1. **User Authentication**:
   - Signup, Login, and Logout functionality.
2. **Landing Page**:
   - Categories and New Arrivals section.
3. **Product Listing Page**:
   - Sort and filter products by price, genre, rating, availability, and delivery options.
   - Clear all filters functionality.
4. **Wishlist Management**:
   - Add/remove items.
   - Move items to the cart.
5. **Cart Management**:
   - Add/remove items.
   - Adjust item quantities.
   - Apply coupons.
   - Move items to the wishlist.
6. **Single Product Page**:
   - Detailed product information.
7. **Order Summary**:
   - View ordered items.
8. **Custom Toast Component**:
   - Notifications for success, error, warning, and information.
9. **Payment Integration**:
   - Razorpay for secure transactions.
10. **Orders Page**:
   - List of previous orders.
11. **Search Functionality**:
   - Search books by name or author.
12. **Pagination**:
   - Navigate through product pages.

## Contribution Guidelines
You are welcome to contribute to this project! Please follow these steps:

1. Fork the repository on GitHub.
2. Clone your fork locally:
   ```bash
   git clone <your-fork-url>
   ```
3. Add the original repository as a remote upstream:
   ```bash
   git remote add upstream <original-repo-url>
   ```
4. Update your local copy with upstream changes:
   ```bash
   git pull upstream development
   ```
5. Create a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
6. Implement your feature and document your changes.
7. Squash your commits into a single meaningful commit:
   ```bash
   git rebase -i HEAD~<number-of-commits>
   ```
8. Push your branch to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
9. Open a pull request targeting the development branch of the original repository.

## Screenshots

### Home Page
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-HomePage-1.PNG)
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-HomePage-2.PNG)
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-HomePage-3.PNG)

### Product Listing Page
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-ProductListingPage-1.PNG)

### User Authentication Pages
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-SignupPage-1.PNG)
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-LoginPage-1.PNG)

### Single Product Page
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-SingleProductPage-1.PNG)

### Wishlist Page
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-WishlistPage-1.PNG)

### Cart Page
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-CartPage-1.PNG)

### Razorpay integration
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-Razorpay_Payment_Integration.PNG)

### Orders Page
![](https://github.com/Naman-Saxena1/Bookztron-E-Commerce_Book_Store/blob/development/src/Assets/Screenshots/Bookztron-OrdersPage-1.PNG)
