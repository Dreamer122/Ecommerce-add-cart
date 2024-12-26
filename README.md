# React + Vite


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
# Project Description


# Project : React Ecommerce Cart

# Summary :
This project is built using ReactJS and allows users to browse products, view detailed information about each product, add products to their cart, and view the items in their cart.

# Components : 
1. Navbar - Displays the navbar at the top of the page.  
2. Products - Render a list of products.  
3. MyCart -  Displays the items added to the cart.  
4. Productdetail - Shows detailed information about a specific product.  

# Routes :
"/": Renders the Products component.  
"/cart": Renders the Mycart component.  
"/product/:id/:name": Renders the Productdetail component.   
The route "/product/:id/:name" is a dynamic route parameterized with two variables: ":id" and ":name". These parameters allow the route to dynamically generate product detail pages based on the product’s unique Id and optionally its name.

# States : 
addcart - Stores the items added to the cart.  
showproduct - Stores the details of the product.  
subTotal - Stores the subtotal amount of all items in the cart.  
showitem - Stores the IDs of products currently displayed in the cart.  

# Functions :
addToCart( ) - Adds a product to the cart. 
handleAmount( ) -  increment and decrement of item quantities in the cart.  
handleSubTotal ( ) - Calculates the subtotal amount of all items in the cart.  
handleDelete( ) -  Deletes an item from the cart.  
TotalAmount( ) -  Calculates the total amount of a specific item.  
ProductShow( ) - Displays detailed information about a specific product.  

# External Libraries : 
React Router DOM - Used for navigation and routing within the application.  
react-hot-toast- Used to show alerts when product added to cart

# Installation : 
npm install react-router-dom   or npm i react-router-dom  
react-hot-toast installation - "npm i react-hot-toast"

# Screenshots of App






![Screenshot (18)](https://github.com/Dreamer122/Ecommerce-add-cart/assets/126068795/e2a28e8b-ee09-47fa-a431-39692add0a65)

![Screenshot (21)](https://github.com/Dreamer122/Ecommerce-add-cart/assets/126068795/3088f49d-7833-4158-8a8a-eba9ad72368a)

![Screenshot (19)](https://github.com/Dreamer122/Ecommerce-add-cart/assets/126068795/22f10183-9199-4252-8799-edaabb15a1ca)

