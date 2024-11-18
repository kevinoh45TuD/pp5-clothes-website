# Clothes Store

## Introduction

This project was created using Django. It is meant to emulate a restaurant website for customers to book a table.

It has been deployed on Heroku, the repository uses Code Institute's template.

[Link to Site](https://pp5-clothes-website-5111351d0c7a.herokuapp.com)

Below I will outline key aspects of the project and its creation.

## Table of Contents

1. [UX](#ux)
    - Epics
    - User Stories
2. [Features](#features)
    - Temp
3. [Technologies Used](#technologies-used)
    - Python
    - Django
    - Heroku
    - HTML
    - Packages
4. [Testing](#testing-1)
    - 
5. [Deployment](#deployment)
    - Setting Up Repository
    - Deploying on Heroku
    - Clone Repository
    - Fork Repository
6. [Credits](#credits)
    - Code Institute
    - Other

## UX
### Epics

10 Epics were created for this project, these were expanded into user stories. The details of this can be found on the related kanban board [Board](https://github.com/users/kevinoh45TuD/projects/2)

Epics:

1. As a developer, I want to set up development and deploy the
 project correctly, so that the development of the project runs
 smoothly without issues.
2. As a website owner, I want the website to function properly
 and appear inviting to users.
3. As a website owner, I want the website to display the
 products I have for sale in a uniform manner.
4. As a website owner, I want to be able to edit details of
 products, such as edit price, apply sale, remove based on
 availability.
5. As a website user, I want to register an account.
6. As a website user, I want to login and view details.
7. As a website user, I want to be able to click on products for
 further details.
8. As a website user, I want to be able to add products to a
 cart.
9. As a website user, I want to be able to purchase items and
 receive confirmation.
10. As a website owner, I want to create and display upcoming
 store news such as sales so that I can keep customers up to date
 and willing to come back.

### User Stories

User Stories were created based on the above Epics:

1. 
    - A. As a developer, I would like to set up a github
    repository, so that I will have somewhere to maintain and update
    the project files.

    - B. As a developer, I would like to set up my IDE along with
    a virtual environment, so that I will be able to begin coding
    the project.

    - C. As a developer, I would like to set up the django
    project along with required packages, so that I will have all
    the required tools to start developing.

    - D. As a developer, I would like to create the initial home
    screen view and layout, so that the project will be ready for
    early deployment.

    - E. As a developer, I would like to deploy the project to
    Heroku early, so that I can see if there are any issues early
    on.
2. 
    -  A. As a website user, I would like a clear website layout that
    adjusts based on screen size, so that the website is easy
    to navigate regardless of which device I am using.

    - B. As a website user, I would like inviting website colours
    and a readable font, so that the website is enjoyable to
    use and easy on the eyes.

    - C. As a developer, I would like automated code testing, so
    that many user input cases can be tested on a larger scale
    to reduce potential bugs.

    - D. As a developer, I would like manual code testing, so that
    user navigation can be tested to reduce potential bugs.
3. 
    - A. As a website owner, I would like navigation for different
    categories of items, so that types of items can be clearly
    separated for users.

    - B. As a website owner, I would like pagination to occur after
    a select amount of items appear, so that a desired amount
    of items will be shown to users per page.

    - C. As a website owner, I would like ‘on sale’ items to appear
    visually distinct, so that users can quickly and inherently
    identify such items.

    - D. As a website owner, I would like ‘out of stock’ items to
    appear visually distinct, so that users can quickly and
    inherently identify such items.
4. 
    -  A. As a developer, I would like to create a custom admin
    screen/UI, so that the website owner will have easier
    access to certain functionality on the website.

    - B. As a website owner, I would like to create new item
    listings in the admin screen, so that I can easily add new
    stock to website item listings.

    - C. As a website owner, I would like to view current item
    listings in the admin screen, so that I can easily check
    the status of current listings.

    - D. As a website owner, I would like to edit a current item’s
    listing details in the admin screen, so that I can easily
    amend/update specific items when needed.

    - E. As a website owner, I would like to edit a current item’s
    listing price, so that an item's price may be updated
    independently of other details relating to the item.

    - F. As a website owner, I would like to apply a ‘sale’ tag to
    current listings, so that an item can be easily marked as
    such when required.

    - G. As a website owner, I would like to apply an ‘out of stock’
    tag to current listings, so that an item can be easily
    marked as such when required.
5. 
    - A. As a website user, I would like a navigation button to
    register on the home screen, so that I can quickly navigate
    to the desired screen.

    - B. As a developer, I would like a prompt to sign in/register
    when users try accessing some sections that require an
    account, so that they can’t get to specific screens that
    require an account.

    - C. As a website owner, I would like a form to register an
    account, so that all the necessary information is gained
    from the user.

    - D. As a developer, I would like form validation for user
    registration, so that I can make sure invalid information
    isn’t submitted for user details.

    - E. As a website user, I would like confirmation for account
    registration form completion, so that I am confident my
    details have been accepted successfully.
6. 
    -  A. As a website user, I would like the option to login from
    the home screen, so that I can quickly navigate to the
    desired screen.

    - B. As a website user, I would like a prompt to sign in when
    required, so that I only sign in when needed.

    - C. As a website user, I would like an account details screen,
    so that I can check what details are currently associated
    with my account.
    
    - D. As a website user, I would like to be able to update my
    details from the account screen, so that I can amend any
    details that may be incorrect.

    - E.As a website user, I would like to be able to delete
    specific details from the account screen, so that I can remove
    details I don’t want attached to the account.
7. 
    -  A. As a website user, I would like the option to login from
    the home screen, so that I can quickly navigate to the
    desired screen.

    - B. As a website user, I would like a prompt to sign in when
    required, so that I only sign in when needed.

    - C. As a website user, I would like an account details screen,
    so that I can check what details are currently associated
    with my account.

    - D. As a website user, I would like to be able to update my
    details from the account screen, so that I can amend any
    details that may be incorrect.

    - E.As a website user, I would like to be able to delete
    specific details from the account screen, so that I can remove
    details I don’t want attached to the account.
8. 
    - A. As a website user, I would like the home screen to have an
    option to add items to cart, so that I can purchase
    multiple things at once.

    - B. As a website user, I would like the product details screen
    to have an option to add to cart, so that I can add items
    to the cart quicker than returning to the home screen.

    - C. As a website user, I would like to be able to navigate to
    the cart from the home screen, so that I can quickly
    navigate to the item I wish to buy.

    - D. As a website user, I would like a custom cart screen, so
    that I can see all the items I have decided to buy.

    - E. As a website user, I would like to see my total cost and
    discounts on the cart screen, so that I can accurately see
    how much I am spending/saving.
9. 
    - A. As a website user, I would like a purchase button on the
    cart screen, so that I can proceed with my purchase.

    - B. As a website owner, I would like a payment details form, so
    that I can get the correct details from users to process
    payment.

    - C. As a developer, I would like to set up Stripe correctly, so
    that there are no bugs or issues with processing payment.

    - D. As a website user, I would like an order confirmation
    through email after a successful purchase, so that I am
    confident the purchase completed successfully. 
10. 
    - A. As a website owner, I would like a section to display
    upcoming store news, so that I have a spot on the home
    screen to inform users of important information such as
    sales or new stock.

    - B. As a website owner, I would like the ability to create new
    posts from an admin/staff screen, so that it will be easy
    for myself or a staff member to add news when needed.

    - C. As a website owner, I would like the ability to edit
    previous posts, so that I can amend incorrect news quickly
    without hassle.
    
    - D. As a website owner, I would like the ability to remove/hide
    previous posts, so that I can stop users from seeing news
    that no longer applies.

### Wireframes

## Features

## Technologies Used

### Python

### Django

### Heroku

### HTML

### Packages

## Deployment

### Setting Up Repository

### Clone Repository

### Fork Repository

## Credits

### Code Institute

### Other
