# AMAZONA

#  Steps


A. Install Tolls
B. Create React App
C. Create Git Repository
D. List Products
   d.1 create products array
   d.2 add product images
   d.3 render products
   d.4 style products
E. Add Routing
   e.1 npm i react-router-dom
   e.2 create route for home screen
   e.3 create router for product screen
F. Create Node.JS Server
   f.1 run npm init in root folder
   f.2 Update package.json set type: module
   f.3 Add. js to imports
   f.4 npm install express
   f.5 create server.js
   f.6 add start command as node backend/server.js
   f.7 require express
   f.8 create route for / return backend is ready
   f.9 move product.js from frontend to backend
   f.10 create route for api/products
   f.11 return products
   f.12 run npm start
G. Fetch Products from Backend
   g.1 set proxy in package.json
   g.2 npm install axios
   g.3 use state hook
   g.4 use effect hook
   g.5 use reducer hook
H. Manage State by Reducer Hook
   h.1 define reducer
   h.2 update fetch data
   h.3 get state from usReducer
I. Add bootstrap UI Framework
   i.1 npm install react-bootstrap bootstrap
   i.2 update App.js
J. Create Product and Rating Component
   j.1 create rating component
   j.2 create product component
   j.3 use rating component in product component
K. Create product details Screen
   k.1 fetch product from backend
   k.2 create 3 columns for image, info and action
L. Create Loading and Message Component
   l.1 create loading component
   l.2 use spinner component
   l.3 create message component
   l.4 create utils.js to define getError function
M. Implement Add To Cart
   m.1 Create React Context
   m.2 define reducer
   m.3 create store provider
   m.4 implement add to cart button click handler
N. Complete Add To Cart
   n.1 check exist item in the cart
   n.2 check count in stock in backend
Ñ. Create Cart Screen
   ñ.1 create 2 columns
   ñ.2 display items list
   ñ.3 create action column
O. Complete Card Screen
   o.1 click handler for inc/dec item
   o.2 click handler for remove item
   o.3 click handler for checkout
P. Create Signin Screen
   p.1 create sign in form
   p.2 add email and password
   p.3 add signin button
Q. Connect To MongoDB Database
   q.1 create atlas mongodb database
   q.2 install local mongodb database
   q.3 npm install mongoose
   q.4 connect to mongodb database
R. Seed Sample Data
   r.1 create product model
   r.2 create seed route
   r.3 use route in server.js
   r.4 seed sample product
S. Seed Sample Users
   s.1 create user model
   s.2 seed sample users
   s.3 create users routes
T. Create Signin Backend API
   t.1 create signin api
   t.2 npm install jsonwebtoken
   t.3 define generateToken