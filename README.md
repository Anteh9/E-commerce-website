## Note: PLease my uml use ase diagram is in the Master branch

# E-commerce-website
 E-commerce Website, the actors and functions typically include the following:

 ## Actors:
1. ## Customer (End User):
   - Represents a person who browses and interacts with the website to make purchases.

2. ## Administrator (Admin):
   - Manages the website's content, processes orders, and handles user-related tasks.

3. ## System (Automated System):
   - Represents the system itself, which performs operations such as payment processing, inventory management, etc.

### Use Cases (Functions/Processes):

## Customer:
1. Register/Log In: Allows customers to create an account or log in to their existing account.
2. Browse Products: Allows customers to view different products available on the website.
3. Search for Products: Allows customers to search for specific products based on various filters (e.g., price, category).
4. View Product Details: Provides detailed information about a product (e.g., price, description, reviews).
5. Add to Cart: Enables customers to add selected products to their shopping cart.
6. Make Purchase: Allows customers to checkout and make payments for the items in their cart. 
7. Track Orders: Enables customers to track the status of their orders after purchase.
8. Write Reviews: Customers can leave reviews or ratings for products they've purchased.
9. Apply Discount/Coupon: Use of promotional codes or discounts during the checkout process.

##  Administrator:
1. Manage Product: Add, update, or remove products from the site.
2. Process Orders: Admin can view orders, approve them, and send them for shipping.
3. Manage User Accounts: Create, update, or delete customer accounts.
4. View Customer Reviews: Admin can view reviews left by customers.

## System:
1. Process Payments: Handles payment transactions securely.
2. Send Confirmation Emails: Automatically sends order and shipping confirmation to customers.
3. Update Inventory: The system updates product availability after purchase.
4. Authenticate User: The system verifies customer login credentials.


## EXtends and Includes
# Includes
1. Register/login :
      Authenticte user 
2. Browse Product:
       view Product details
3. Make Purchase:
       Process Payment,send confirmation  


# Extends
1. Browse Product:
      Add to cart
2. Make Purchase :
      Apply Discount, Write Reviews
