# She Rydes 
## A fullstack MERN e-Commerce website.
![](/Docs/caferacer2.jpg)
## By Junior Developers:
#### [Alison Killen](https://github.com/alikillen)
#### [Sevda Amini](https://github.com/Sevicode)


### Link to Repositories:
Documentation: https://github.com/Sevicode/SevliMERN_partA/tree/master

Project:

### Table of Content
[Project Description](#Project-Description)

[Purpose](#Purpose)

[Functionality and Features](#Functionality-and-Features)

[Target Audience](#Target-Audience)

[Tech Stack](#Tech-Stack)

[Sitemap](#Sitemap)

[Dataflow Diagram](#Dataflow-Diagram)

[Application Architecture Diagram](#Application-Architecture-Diagram)

[User Stories](#User-Stories)

[Wireframes](#Wireframes)

* [Mobile Wireframes](#Mobile-Wireframes)
* [Desktop Wireframes](#Desktop-Wireframes)

[Project Management](#Project-Management)
* [Trello](#Trello)


## Project Description
This project is a MERN full-stack web application which we developed as a part of our final Coder Academy Bootcamp assignment. Throughout this project we worked as a team of two junior developers and developed an e-commerce store where users (customers) can sign in, browse and view products, and learn about the brand She Rydes. The seller (client) is also an admin on the site and has full authorization to manage the website and make changes in the listings. 

## Purpose
*She Rydes* is a real world project and the client aims to bring a convenient and affordable place for people and specifically female customers to purchase their motorcycle riding apparrel. The client needs a fast, well-designed responsive website that reflects their brand and has detailed eCommerce functionality, allowing customers to browse and purchase apparel with ease.

## Functionality and Features
Our team have tried their best to integrate the client's requested features in the application as best as possible and meet their expectations:

* Login/out and Signing up : a customer needs to sign in and if not previously signed up, they will have to sign up to be able to make a purchase or review a product.
* Admin panel : the client/seller has the admin role and is fully authorized to make changes in the listings. 
* Product Rating : customers can leave reviews for the products they have purchased and rate them. A star rating system is designed so the customers can rate the purchased pproducts between 1-5 star. 
* User Authentication : Users need to be signed in either as a customer or admin/seller. This will be checked with authentication functionality already added to the application, including Front and Back-end use authentication and frontend profile. 
* Shopping cart: customers can add products to their shopping cart. 
* Payment systems - VISA, Mastercard and PayPal supported with vision to later include ZipPay

## Target Audience

The target audience is female motorcycle riders between approx. 23 and 39 years of age. The client also wants to predominantly target Australian riders, especially as she is in the initial phases of establishing and growing her business. The potential customers will be “urban dwellers who enjoy adventuring”, as specified by the client.

The “cafe racer” bike (pictured above) will be the typical bike style for the apparel - the client does not want to reflect sports or off road bikes in her branding - she states “She Rydes will have a subtle city meets sea vision, being bred on the Gold Coast and with a lot of coastal Australian riders, the brand will deter away from the ‘rough bikie in the dessert’ image and more towards a relaxed surf lifestyle. There are enough skulls, tassels & vests around. It’s time to associate an emerging market with sophistication and practicality.” This sophistication and practicality is to be reflected in the website’s design and the apparel the client is designing and selling.



## Tech Stack

The website will be built with the MERN stack with additional ecommerce functionality. We will build the website from scratch, enabling full customizability. We will use MongoDB as our database for its scalability and flexibility. We will use express and node to enable our backend routing. React will be used to enable our fast and responsive front-end design, and to connect our frontend CRUD routes to our backend CRUD routes. We will implement ecommerce features to enable secure payment on the website.

**Planning/Design Tools:**

- Figma
- Balsamiq
- Draw.io

**Frontend:**

- HTML5
- CSS3
- ReactJS
- Javascript
- JSX
- Bootstrap
- Axios

**Backend:**

- NodeJS
- ExpressJS
- Stripe
- AWS S3

**Node Dependencies**

- Nodemon
- React-bootstrap
- Express
- Cors

**Database:**

- MongoDB
- Mongoose

**Testing:**

- Jest
- Cypress

**Deployment:**

- Heroku
- Zuber

**API's:**
- Google Maps API
## Sitemap

![](/Docs/sitemap.jpg)
## Dataflow Diagram
![](/Docs/DFD-Page-1.png)


![](/Docs/DFD-Page-2.png)


![](/Docs/DFD-Page-3.png)


![](/Docs/DFD-Page-4.png)


![](/Docs/DFD-Page-5.png)

## Application Architecture Diagram
![](/Docs/AAD.png)
## User Stories

### User MVP features: 

- As a user, I can easily navigate all pages of the website on my phone, tablet or PC
- As a user, I’m impressed by the sleek look of the website and it intrigues me about the brand it represents
- As a user I can easily browse through the She Rydes social media which is visible from the website
- As a user, I’m able to easily see the contact information of the business and the returns policy from the website, so I feel confident in my trust of the business
- As a user, I can quickly and easily browse through the ranges of apparel that are available
- As a user I can see prices and details of the products clearly
- As a user I can access a sizing chart
- As a user, I can create an account
- As a user, I can login
- As a user, I can add items to my cart
- As a user, I can confidently and securely purchase apparel with minimum fuss + clicks
- As a user, I can see shipping rates that are calculated at checkout

### User Additional features:
- As a user, I can review a product and leave a star rating
- As a user, I can login with google or facebook
- As a user, I can get discounted products when I enter a promo code
- As a user, I can subscribe at checkout or in the footer to receive updates about promotions and discounts

### Administrator stories:

### Admin MVP features:
- As an administrator I can login
- As an administrator I can edit products, delete products, add promotions etc
- As an administrator I can change photos for products

### Admin Additional features:
- As an administrator, I can see the google analytics of my website
- As an administrator I can change photos and colours on the website
- As an administrator, I can view and edit my inventory/stock levels
- As an administrator, I can write newsletters to customers with events, news and promo codes for discounts
- As an administrator I can modify the SEO for my website
- As an administrator I have a custom email with the domain of the website


### User Personas

Below are some of the types of users the site will be designed to attract.

| Name, Age, Location, Occupation |              Hobbies             |                 Persona                 |                                       Why use She Rydes? How’d they find it?                                      |       What are they looking for in a website?       |       Values      |
|:-------------------------------:|:--------------------------------:|:---------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------:|:-----------------:|
| Samantha, 22, Byron Bay, nurse  | Crafting jewelry, film, singing. | Creative, hardworking, community-minded | Started riding 4 years ago and needs to upgrade her gear. Was referred by a friend who recently purchased gloves. | Accurate and detailed photos, mobile responsiveness | Style, durability |

|  Name, Age, Location, Occupation  |          Hobbies          |            Persona            |                   Why use She Rydes? How’d they find it?                  | What are they looking for in a website? |                Values                |
|:---------------------------------:|:-------------------------:|:-----------------------------:|:-------------------------------------------------------------------------:|:---------------------------------------:|:------------------------------------:|
| Alex, 26, Brisbane, Web developer | Gaming, Drawing, Swimming | Modern, inquisitive, generous | Looking to buy a gift for his partner. Girlfriend saw an ad on instagram. | Speed, ease of checkout                 | Efficiency, clarity, stylish attire. |

|    Name, Age, Location, Occupation   |                                         Hobbies                                         |             Persona            |                                                       Why use She Rydes? How’d they find it?                                                      |                                   What are they looking for in a website?                                  |                          Values                          |
|:------------------------------------:|:---------------------------------------------------------------------------------------:|:------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------:|
| Mary, 43, Gold Coast, retail manager | Experienced with long-haul rides around the country in all conditions. Surfing, hiking. | Outdoorsy, fitness, travel fan | Has just moved to the Gold Coast, is looking for more casual gear to wear while riding around town. Saw an ad in the local facebook riders group. | Accurate descriptions of merchandise, clear sizing charts, ability to return gear if it doesn’t fit right. | Durability of garments, fair price, attention to detail. |


## Wireframes
### Mobile Wireframes

![](/Docs/wireframes/Mobile_Home.png)
![](/Docs/wireframes/Mobile_contact.png)
![](/Docs/wireframes/Mobile_individual.png)
![](/Docs/wireframes/Mobile_Products.png)


### Desktop Wireframes

![](/Docs/wireframes/Desktop_Home.png)
![](/Docs/wireframes/Desktop_Login.png)
![](/Docs/wireframes/Desktop_AboutUs.png)
![](/Docs/wireframes/Desktop_ContactUs.png)
![](/Docs/wireframes/Desktop_ShoptheLook.png)
![](/Docs/wireframes/Desktop_Products.png)
![](/Docs/wireframes/Desktop_individual_product.png)
![](/Docs/wireframes/Desktop_Cart.png)
![](/Docs/wireframes/Desktop_AccountSettings.png)
![](/Docs/wireframes/Desktop_Shipping.png)


### Tablet Wireframes
![](/Docs/wireframes/Tablet_Home.png)
![](/Docs/wireframes/Tablet_Login.png)
![](/Docs/wireframes/Tablet_Cart.png)
![](/Docs/wireframes/Tablet_Product_Range.png)
![](/Docs/wireframes/Tablet_individual.png)

## Project Management
We followed the Agile methodology of working to deliver the maximum work in the time allowed. We broke the requirements into smaller tasks and prioritised them based on their importance, and each team member was assigned with a list of tasks and a timeframe. We used Trello for this purpose and used Discord for the online communications. We also created a shared folder on Google Drive to allow for quick amalgamation of documents from the client. The following are screenshots of our Trello board showing how our tasks have been changed and updated during our work on this project.

### Trello 

![](/Docs/2020-11-24.png)
![](/Docs/2020-11-30.png)
![](/Docs/2020-12-01.png)

## Presentation
