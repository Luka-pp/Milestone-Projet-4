## TESTING

### User Stories

For this website there is generally two types of users. One is the customer who is looking to purchase the plants form
the shop with ease, convenience and in a safe way. The other one is the shop owner whose goals are to provide users with
the nice and secure shop and to benefit from it.

![User Stories ](/Testing%20and%20Readme%20media/Images/user_stories.png)

Link for sorting options is [here](/Testing%20and%20Readme%20media/Images/sorting.png)

### Fulfilment of user stories

![User Stories Fulfilment ](/Testing%20and%20Readme%20media/Images/user_stories_fulfilment.png)

![Site Owner User Stories Fulfilment ](/Testing%20and%20Readme%20media/Images/site_owner_stories_fulfilment.png)

### **Code Validation**

**HTML**

All the pages on the website have been put through W3C Markup Validation Service. Most of the errors are related to teh
django templating logic and as such i do nok know yet how to fix.

Errors discovered:

- Element li not allowed as child of element nav in this context. (Suppressing further errors from this subtree.)
  Still awaiting fixing.

**CSS**

Code has been through **W3C CSS Validation Service** and there were no errors found.

**Javascript**

All the **Javascript** code has been passed through JSHint. There was one issue discovered (missing semicolon)
on ``stripe_elements.js`` which was fixed. There was no other issues detected with Javascript.

**Python**

All the Python files have been checked by **PyCharm's** included PEP8 validator. There were few issues detected with
missing new blank lines at the end of the code. All of those are resolved.

**Form Validation**

All the forms are validated with HTML. Manual testing has been carried out for the forms to confirm they are working
correctly.

### Defensive programming

Some pages can be accessed only by authorized users. This is to prevent users accessing sensitive information.

**Product Management** Page is only accessible by the SuperUser.

**My Profile** page is only available for the registered users.

**Edit and Delete** button on the products are available only to the SuperUser.

**Blog Comments** Can be posted by anyone but will only be displayed if administration / site owner approves them.

### Browser testing

Desktop

Website performs as intended on desktop PC and on a Laptop running Windows 10 with the latest version of browser in
question.

1. Chrome

    - Everything in perfect order, no layout loss, all functions of website work as intended. Forms and validations work
      as intended.

2. Opera

    - Everything in perfect order, no layout loss, all functions of website work as intended. Forms and validations work
      as intended.

3. Mozilla

    - Everything in perfect order, no layout loss, all functions of website work as intended. Forms and validations work
      as intended.

Mobile

1. Device / browser

    - One Plus 8T / Chrome: Layout works as intended, All the animations work perfectly. Forms are looking good and
      navigation works perfectly.
2. Device / browser

    - Apple Iphone 12 / Safari: Layout works as intended, All the animations work perfectly. Forms are looking good and
      navigation works perfectly.

3. Device / browser

    - Apple Iphone 12 / Chrome: Layout works as intended, All the animations work perfectly. Forms are looking good and
      navigation works perfectly.

### Functionality of website

1. Responsiveness

    - Bootstrap library is in charge of the grid and responsiveness. By using their grid I was able to scale website
      from the smallest of screens to the large desktops. Mobile dropdown navigation works great and quick.

2. Links

    - All the links on the website have been manually tested and all of them are leading to the intended destinations.
      Social links currently lead to home pages of the social networks as the business social pages are not created.
      Tested both on mobile device and on PC.
3. Buttons

    - All the buttons have been tested manually. All buttons work and their actions work as intended. Tested both on
      mobile device and on PC.
4. Forms

    - All the form are working as intended, and they interact well with the database.
5. Database

    - Database performs well, all the necessary data is stored and accessed as needed.
6. Deployment

    - Website has auto deployment from **GitHub** enabled. That means every time I push the content from my local
      repository to the remote repository new website build gets created. At the time of writing this the website was on
      version 115.
7. AWS Amazon Web Services

    - All the static and media files are being hosted on AWS using their S3 free tier service.

### Bugs, Errors, Issues and fixes

While developing and performing testing on this application I have encountered a lot of errors and issues, below are
some of them:

- At the beginning of the development Bootstrap did not work at all. Issue was fixed by selecting correct version of
  Bootstrap CDN.
- While I was building fixtures for the database I have misspelled Macrame Hangers so the products and that specific
  category did not work. After fixing the typo everything worked as intended.
- while freezing requirements with pip i have made another typo in the word, and I could not deploy the application on
  Heroku. After fixing the spelling, application was deployed successfully.
- While creating S3 bucket AWS i have written majestic plants for the name but in the settings.py i have entered
  majestic-plants. After discovering it, I corrected the name and managed to load static and media files.
- I had issues with virtual environment in PyCharm. Somewhere along the project I have somehow exited the virtual
  environment in the terminal. That broke complete application. After consultations with My mentor Spencer and few tutor
  support sessions I was able to get back on the track of my development.
- At the end of the project I have set up the actual emails being sent from Gmail. After a week of code checking and
  hour of googling I have discovered I forgot to turn DEBUG off in Heroku config vars. After I removed that config vars
  emails were sent with no issues. This was tested by temp emails.
- Fixed navigation overflow issue on the smallest screens (iphone 5 on dev tools in chrome) by adjusting padding on the
  navigation.

