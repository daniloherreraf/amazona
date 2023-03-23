# AMAZONA

#  Steps


A. Install Tolls
<hr/>
B. Create React App
<hr/>
C. Create Git Repository
<hr/>
D. List Products
   d.1 create products array
   d.2 add product images
   d.3 render products
   d.4 style products
<hr/>
E. Add Routing
   e.1 npm i react-router-dom
   e.2 create route for home screen
   e.3 create router for product screen
<hr/>
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
<hr/>
G. Fetch Products from Backend
   g.1 set proxy in package.json
   g.2 npm install axios
   g.3 use state hook
   g.4 use effect hook
   g.5 use reducer hook
<hr/>
H. Manage State by Reducer Hook
   h.1 define reducer
   h.2 update fetch data
   h.3 get state from usReducer
<hr/>
I. Add bootstrap UI Framework
   i.1 npm install react-bootstrap bootstrap
   i.2 update App.js
<hr/>
J. Create Product and Rating Component
   j.1 create rating component
   j.2 create product component
   j.3 use rating component in product component
<hr/>
K. Create product details Screen
   k.1 fetch product from backend
   k.2 create 3 columns for image, info and action
<hr/>
L. Create Loading and Message Component
   l.1 create loading component
   l.2 use spinner component
   l.3 create message component
   l.4 create utils.js to define getError function
<hr/>
M. Implement Add To Cart
   m.1 Create React Context
   m.2 define reducer
   m.3 create store provider
   m.4 implement add to cart button click handler
<hr/>
N. Complete Add To Cart
   n.1 check exist item in the cart
   n.2 check count in stock in backend
<hr/>
Ñ. Create Cart Screen
   ñ.1 create 2 columns
   ñ.2 display items list
   ñ.3 create action column
<hr/>
O. Complete Card Screen
   o.1 click handler for inc/dec item
   o.2 click handler for remove item
   o.3 click handler for checkout
<hr/>
P. Create Signin Screen
   p.1 create sign in form
   p.2 add email and password
   p.3 add signin button
<hr/>
Q. Connect To MongoDB Database
   q.1 create atlas mongodb database
   q.2 install local mongodb database
   q.3 npm install mongoose
   q.4 connect to mongodb database
<hr/>
R. Seed Sample Data
   r.1 create product model
   r.2 create seed route
   r.3 use route in server.js
   r.4 seed sample product
<hr/>
S. Seed Sample Users
   s.1 create user model
   s.2 seed sample users
   s.3 create users routes
<hr/>
T. Create Signin Backend API
   t.1 create signin api
   t.2 npm install jsonwebtoken
   t.3 define generateToken
<hr/>
U. Complete Signin Screen
   u.1 handle submit action
   u.2 save token in store and local storage
   u.3 show user name in header
<hr/>
V. Create Shipping Screen
   v.1 create form inputs
   v.2 handle save shipping address
   v.3 add checkout wizard bar
<hr/>
W. Create Sign up Screen
   w.1 create input form
   w.2 handle submit
   w.3 create backend api
<hr/>
X. Implement Select Payment method Screen
   x.1 create input forms
   x.2 handle submit
<hr/>
Y. Create Place order Screen
   y.1 show cart items, payment and address
   y.2 handle place order action
   y.3 create order create api
<hr/>
Z. Implement Place Order Action
   z.1 handle place order action
   z.2 create order create api
<hr/>
AB. Create Order Screen
   ab.1 create backend api for order/:id
   ab.2 fetch order api in frontend
   ab.3 show order information in 2 columns
<hr/>
AC. Pay order By PayPal
   ac.1 generate paypal client id
   ac.2 create api to return client id
   ac.3 install react-paypal-js
   ac.4 use PayPalScriptProvider in index.js
   ac.5 use usePayPalscriptReducer in Order Screen
   ac.6 implement loadPayPalScript function
   ac.7 render paypal button
   ac.8 implement onApprove payment function
   ac.9 create pay order api in backend
