![Logo Image](media/majestic_plants_logo.png)

# Majestic Plants


For my **Milestone Project 4** on **Code Institute's Diploma in Software Development** course I have created a
e-commerce website for selling plants. Majestic Plants is a start-up company 
which is specializing in sales of healthy and unique plants. There is also some
of the crowd favorites in there!

For link to the website click [Here](https://majestic-plants.herokuapp.com/)

Application is designed for all screen sizes.

![Am I Responsive](image to come here)


## Who is this application for?

This application is for all the plant lovers ot there. It is designed to be user friendly and that 
anyone can go ahead and get that plant they really want. It is also designed
for the store owner who wants to start his new business and is and is a huge fan 
of plants!

## What does it do?

Store owner can display his plants and offer them to the customers to buy. 
Plants are presented in all of their glory and the customer knows exactly what they are getting.
Checkout and payments are done in a hassle-free way so that everyone has a pleasant experience.
Delivery can be provided for a small fee and **Majestic Plants** are **delivering worldwide!**


## User Experience

## UX 5 Planes

### Strategy Plane
Goal of the website was to create a fully functional e-commerce application
while showcasing the Django Frameworks. This application showcases all the amazing features
that Django Frameworks can offer. Users have opportunity to log in, register and make their
profiles with information that will make their checkout in future easier.
Blog feature adds a new dimension to the application. With blog customers can interact with 
one another. This can also serve as a good indication to the shop owner to see the demand for certain plants.
Store owners can also get a feedback from customers which can then improve their service.

### Scope Plane
Based on the requirements of achieving user's and owner's goals and stories, here is the list of required  
 features and functions. CRUD (Create, Read, Update, and Delete) functions are implemented on the website 
as it is required for owners product management.

- simple and effective landing page with call-to-action button.
- Products app shows all the available products which are presented in a well-structured and appealing way
- Sorting products in main navigation is available and helpful for the user to filter out exactly what he/she wants
- Search option is available for the user and store owner to find a particular product
- Shopping bag page is created for the user to be able to summarize their shopping and also to be able to adjust it
- Login and register pages are created so the users can personalize their experience
- Product management page helps site owner adding, deleting or editing products, more conveniently site owner can browse the all products page and use edit or delete buttons under each shop item to make changes
- Profile app saves users details to help with future transactions. Page also provides user with the history of their orders
### Structure Plane

#### Header and navigation
Header is the same through the whole page and consists of:

First Row:
- Majestic plants logo text which is a link redirecting users to the home page
- Search bar area for users to find items in the shop
- Account button which opens drop down menu for the user to login or register. If user is superuser product management link also appears
- Bag button which directs user to the Shopping bag page and is updated with the price after user adds items to the bag

Second Row:
- Home button which redirects user to the landing page
- All Products, Plants, Pots and Hangers and Special offers buttons which open drop down menus each for their respective purpose. Each button helps users filter and arrange products to their liking
- Blog button which redirects user to the Blog page

#### Footer

Footer consists of floating social icons which are consistent throughout the whole site

#### Landing Page

Landing page consists of header, footer and main call-to-action button which redirects user to the all products page.
Page features image of the deep forest in the mist.

#### Products page

This page features all products in the shop.
Each product is represented with an image, name, price, category and rating for it.
By clicking on the image user is redirected to the product detail page.

#### Product Detail Page

This page consists of large image of the product on the left.

On the right there is:
- name
- price
- category
- rating 
- quantity with + and - buttons to select the amount of the product user wants to buy
- keep shopping button which redirects user to the all products page
- add to bag button which adds the product to users bag

#### Shopping bag page

This page consists of list of products in the users bag. 

Each list row consists of:
- product image
- product name and SKU
- product price
- buttons for changing quantity
- subtotal button

At the bottom of all the products in the page on the right side there is:
- Bag total which shows to customer how much is total price of the shopping bag
- delivery cost 
- grant total figure for the whole shopping bag including delivery
- message on how much the customer needs to spend more to avail of the free delivery. This message disappears if customer reaches over £30 in the bag
- keep shopping button which redirects customer to all products page
- secure checkout button which redirects user to the checkout page

#### Checkout pages
Checkout Page:
- This page consists of contact form on the left which customer needs to fill in with his/hers details and order summary on the right.
- on the bottom of there are 2 buttons which either redirects user back to bag for adjustments or to securely complete order using stripe secure checkout

On the click of the **Complete Order** button user is redirected to the checkout success page.

Checkout success page:
- Consists of short confirmation message with the email of the customer and an order summary.
- Button on the bottom of the page which will redirect user tro the special offers page

Overlay with the large spinner is created in transition between 2 pages.

#### Account Pages

Accounts button on the navigation gives user an option to log in or to register.
If the user is superuser the option for product management is shown as well.

Login page consists of a form in which user have to type in his/hers username and password and is then redirected to the
home page.

Register page consists of the form in which user needs to enter their email, username and password to create new account.

Log Out page gives user an option to log out from their account.

#### Blog Page

text to follow


### Surface Plane



### Skeleton Plane

## Features

### Existing features

### Features left for future implementation

## Technologies used

## Resources

## Testing

## Version Control

### Git and GitHub

## Deployment

## Database

