# Final Project

## Requirements

You will build a basic E-commerce application using the Fake Store API to retrieve product data.

## Use fake products api
 - https://fakestoreapi.com/

## The app will have the following 4 pages:

- Products page

  - Display the image, title, and price of all products in a list or grid.
  - When a product is clicked, navigate to the detail page for the selected product.

- Product Details Page

  - Display all product details (image, title, price, category, description)
  - Display a "Quantity" input with default value of 1
  - Display an "Add to Cart" button
  - When the "Add to Cart" button is clicked, the product and quantity should be added to the cart

- Cart Page

  - Display a list of the products and their quantities in the cart
  - Allow products to be deleted from the cart

- Checkout Page

  - Display the name, price, and quantity of all items in the the cart
  - Display the total cost of the cart.
  - Display a checkout form with inputs for
    - Name
    - Shipping address
    - Billing address
    - Credit card info
    - Submit button
  - submitting the order for should clear the cart and return to main product lists page

## Use React Router to handle navigation between pages

- / → Products Page
- /products/:id → Product Details Page
- /cart → Cart Page
- /checkout → Checkout Page

Use Context to maintain a global Cart state.

- The Context store should provide the following functionality
  - Get cart state
  - Add a product and its quantity to the cart
  - Update the quantity of a product
  - Remove a product from cart

## Optional (Bonus)

- Allow filtering products by category
- Allow filtering products by search term
- Allow ordering products by price (lowset to highest, highest to lowest)
- Allow updating product quantity in the cart
- On a product detail page, show a list of similar or recommended products
