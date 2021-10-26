![Logo Image](media/majestic_plants_logo.png)

# Majestic Plants


For my **Milestone Project 4** on **Code Institute's Diploma in Software Development** course I have created a
e-commerce website for selling plants. Majestic Plants is a start-up company 
which is specializing in sales of healthy and unique plants. There is also some
of the crowd favorites in there!

For link to the website click [Here](https://majestic-plants.herokuapp.com/)

Application is designed for all screen sizes.

![Am I Responsive](/Testing%20and%20Readme%20media/Images/am_i_responsive.png)


## Who is this application for?

This application is for all the plant lovers ot there. It is designed to be user-friendly and that 
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

Blog page features blog posts displayed as cards with short description and a button to open a blog detail page. 
Each blog post card also features authors name and the date and time when it was posted.

Blog details page features full version of the blog post with all of its details. This page also features 
the comments section.

Underneath the blog post comments are displayed with the time and date comment was added.
underneath all the comments form is displayed where users can add their comments.

Form consists of 3 mandatory fields and a button:
- Name: for user to select the name under which the comment will be posted
- Email: where user needs to add a conditional formatting
- Body: where users write the content of their comment
- Submit button: submits users comment

Administrator of the website needs to approve each one of the comments. If the comment 
is not approved it will not be displayed.

Comments are approved in Django's admin console.


### Surface Plane

Website has been designed with the focus on the product.
Throughout the website black and white colours interchange and the first thing that is vibrant 
are the products pictures. As this website is selling plants I wanted to focus fully on the 
amazing colours and patterns mother nature is presenting us with.

#### Typography

The font has been acquired from **Google Fonts**, and to suit the overall looks of the website
**Teko** font has been used in black and white color.

### Skeleton Plane

This website is designed to be used on all the screen sizes.

Wireframes and their evolution can be found [here](link to go here for the wireframes).

## Features

### Existing features
- Created in HTML, CSS, Javascript, Python, Django and Bootstrap
- Local database for development was **sqlite3**
- Deployed website uses **PostgresSQL Database** provided by **Heroku**
- Full CRUD functionality 
- Log In, Log Out, Register functions implemented
- Email user verification synchronised with **Gmail**
- Full **Stripe** integration
- Database querying and sorting all the available products
- Fully functional Blog section with enabled but supervised user comments

### Features left for future implementation
- Adding more images for the same product
- Social Websites
- Membership program
- Wishlist for customers
- Real Time Chat

## Technologies used

* [HTML5](https://en.wikipedia.org/wiki/HTML) for markup
* [CSS3](https://en.wikipedia.org/wiki/CSS) for style
* [Python](https://www.python.org/) for backend development
* [Django](https://www.djangoproject.com/) for frameworks
* [PostgreSQL](https://www.postgresql.org//) as the database for the website
* [Git](https://git-scm.com/) for version control
* [GitHub](https://github.com/) as a remote repository
* [Bootstrap](https://getbootstrap.com/) for main frame and styling
* [JavaScript](https://www.javascript.com/) For functionality of some parts of website
* [PyCharm](https://www.jetbrains.com/pycharm/) As my main editor and local repository
* [Heroku](https://www.heroku.com/) For deployment of the website

## Resources

* [pixabay](https://pixabay.com/) for images with free license
* [Code Institute](https://codeinstitute.net/) course materials
* [Code Institute Slack](https://codeinstitute.net/) Slack Community
* [MDN](https://developer.mozilla.org/en-US/) general help and pointers
* [Stackoverflow](https://stackoverflow.com/) general help and pointers
* [Youtube](https://www.youtube.com/) general help and pointers
* [W3schools](https://www.w3schools.com/) general help and pointers
* [Am I Responsive](http://ami.responsivedesign.is/) for a responsive image in Read Me
* [Soda PDF](https://www.sodapdf.com/jpg-to-pdf/) to convert images to PDF
* [LogoMakr](https://logomakr.com/) for creation of the logo
* [Google](https://www.google.ie/) general help
* [TempMailo](https://tempmailo.com/) for temporary email addresses while testing
* [DJANGOCENTRAL](https://djangocentral.com/) for help with blog application
* [Google Fonts](https://fonts.google.com/) for the font used throughout the website
* [Font Awesome](https://fontawesome.com/) for icons
* [Stripe](https://stripe.com/ie) for help with payments integration
* [AmazonWebServices-AWS](https://aws.amazon.com/) for hosting static and media files

**All the plant images come from my own private collection**

## Testing

Testing has been done and documented
in [Testing.md](link here)

## Version Control

### Git and GitHub

I used **[PyCharm](https://www.jetbrains.com/pycharm/)** as a local repository and IDE
and **[GitHub](https://github.com/)** as a remote repository. The process of version control was:

* First I created a new repository on GitHub
* I have then connected my GitHub account and my PyCharm IDE
* I have then opened that repository in PyCharm and started coding
* In PyCharm I have created all the pages and folders
* I was then saving my work and pushing it to GitHub repository to keep it safe
* Process for saving, committing and pushing it to remote repository goes as follows:
* In the main window of PyCharm click on **Git**
* On drop down menu click on **Commit**
* The commit interface will open on the left side and after adding the commit message click on commit in the left bottom
  corner
* Work is now committed to the master branch
* To push that commit to the **GitHub** I clicked on **Commit and Push** button in the same window
* On click on **Commit and Push** button the pop-up window will show where I needed to confirm that I want to push the
  work to my GitHub repository

## Deployment

This project requires back-end technologies, so for the deployment [Heroku](https://www.heroku.com/) was used. 
**Heroku**, a cloud platform where users can host their projects. This platform offers free sand paid service. For
the purpose of this project free version was enough. **PostgreSQL** database was selected from
free Heroku addons. For hosting of static files and media files **AWS** S3 bucket was used on a free plan.

Heroku setup:
- Creating account on **Heroku**
- Creating new app by clicking on *New* and then *Create new app*
- Type in the unique name on the app and choose a region closest to us for deployment
- Provision **PostgreSQL** database from heroku add-ons

Steps to be taken before deployment:

- installing **dj_database_url** and **psycopg2-binary** via **pip** from PyCharm terminal
- Connecting local database to **PostgreSQL** by changing ``DEFAULT_DATABASE`` with **database URL** from Heroku and running migrations on our project
- importing all the fixtures by running commands **python manage.py loaddata categories** and **python manage.py loaddata products**
- creating **superuser** by running **python manage.py createsuperuser**
- instilling **unicorn** via pip which will act as our webserver
- **Requirements.txt** file created using **pip freeze > requirements.txt**. This file contains all the necessary dependencies so Heroku can have them ready for the project
- **Procfile** this file contains necessary details about the project so that heroku know what and where is he deploying and in
      which programming language
- temporarily disable ``collectstatic``
- adding host name of our Heroku app to ``settings.py``

Before enabling automatic deploys, Config Vars have to be set as [this](https://github.com/Luka-pp/Milestone-Projet-4/blob/master/Testing%20and%20Readme%20media/Images/heroku_config_vars.png) image indicates
**Settings**.
When all the hidden variables done, click **Enable Automatic Deploys** and click **Deploy Branch*
- Once app deploys the confirmation message will be shown


## Database
During the development **sqlite3** database was used which is installed with **Django**.
For deployment(production), a PostgreSQL database is provided by Heroku as an add-on.

Fixtures for the products are taken from the **Code Institute** course material and manually altered
to fit this project. 

Fixtures are then loaded into the database via **CLI** from the **Pycharm**.
Using the command **python manage.py loaddata categories** to first load the categories for the products
as they are needed for the products fixture. 

Products are then loaded using command **python manage.py loaddata products**. 

After running necessary **migrations** basic products and categories are loaded into database.


### Special thanks to my mentor Spencer Barriball for help and advice throughout the development!