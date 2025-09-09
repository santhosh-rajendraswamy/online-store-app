### Buhler Online store

A single-page web app that lets Bühler customers explore the latest products and place orders online.

### Demo

A libe demo of the application can be seen [here](https://saddamakhtar88.github.io/online-store-app/)

### Product requirements

1. Header

   - The top bar shall be common across the application. It shall contain 3 elements -

     1. [Buhler logo](logos\buhler-logo.svg) - The logo should be clickable and should land onto "Product List" page on click.
     2. Current date and time.
     3. Cart details - the user should be able to navigate to "Checkout" page on click.

   ![Header](snapshots\header.png)

2. Product list

   - The page shall contain section-wise list of products.
   - You can refer to [products.json](http/products.json) for data structure and sample.
   - Each section shall have a heading followed by list of products.
   - Each product card shall display image, product name, price, and "Add to Cart" button.

   ![Product List](snapshots\product-list.png)

3. Product Details

   - The URL of the page shall contain a unique product identifier (For example. /products/{productId})
   - The page shall contain details of a product - Image, Name, type of product, price, and "Add to Cart" button.
   - The page shall also have the ability to go back to products list page.

   ![Product Detail](snapshots\product-detail.png)

4. Checkout

   - The page shall contain details of items added to cart and sum of prices of products in the cart.
   - Each row shall contain product image, name, type, price, ability to remove product from cart.
   - It should show a "Total" - sum of all the product prices in the cart.

   ![Checkout](snapshots\checkout.png)

### Enhancements Within the Assignment’s Spirit

1. Prefer enhancements that are easy to run, test, and review.
2. Follow clean code practices, consistent formatting, and meaningful naming.
3. Do not change the primary problem statement, user journey, or acceptance criteria.
4. Aim for depth over breadth: a few well-executed improvements beat many partial ones.
5. Documentation and developer experience improvements.
