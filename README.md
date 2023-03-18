# AMAZONA

#  Steps


A. Install Tolls
B. Create React App
C. Create Git Repository
D. List Products
   1. create products array
   2. add product images
   3. render products
   4. style products
E. Add Routing
   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen
F. Create Node.JS Server
   1. run npm init in root folder
   2. Update package.json set type: module
   3. Add. js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move product.js from frontend to backend
   10. create route for api/products
   11. return products
   12. run npm start
G. Fetch Products from Backend
   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook
H. Manage State by Reducer Hook
   1. define reducer
   2. update fetch data
   3. get state from usReducer
I. Add bootstrap UI Framework
   1. npm install react-bootstrap bootstrap
   2. update App.js
J. Create Product and Rating Component
   1. create rating component
   2. create product component
   3. use rating component in product component
K. Create product details Screen
   1. fetch product from backend
   2. create 3 columns for image, info and action
L. Create Loading and Message Component
   1. create loading component
   2. use spinner component
   3. create message component
   4. create utils.js to define getError function
M. Implement Add To Cart
   1. Create React Context
   2. define reducer
   3. create store provider
   4. implement add to cart button click handler
N. Complete Add To Cart
   1. check exist item in the cart
   2. check count in stock in backend
