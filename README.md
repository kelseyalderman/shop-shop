# Shop Shop

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Features](#features)
- [Technologies](#technologies)
- [Website](#website)
- [Installation](#installation)

## Description

An e-commerce platform that handles complex state management using Redux.

## User Story

As a user interested in online shopping, I would like an application that allows me to track items I want to buy in a virtual shopping cart that updates when I add or remove items, and a platform that accepts my payment online for my purchases.

## Features

When first visiting the homepage, users can browse items for purchase and use filters to search for items.

![Video demonstration of Shop Shop](assets/shop-shop-demo-1.gif)

Users can view specific items for more information.

![Video demonstration of viewing items on Shop Shop](assets/shop-shop-demo-2.gif)

Users can add and remove items from their cart and view their cart to see updated items.

![Video demonstration of using the cart on Shop Shop](assets/shop-shop-demo-3.gif)

If a user leaves the web page, the items will be saved in their cart for when they return.

![Video demonstration of using the cart on Shop Shop](assets/shop-shop-demo-4.gif)

Users are prompted to log in to check out from their cart. After signing up or logging in, users are able to purchase the items from their cart.

![Video demonstration of using the cart on Shop Shop](assets/shop-shop-demo-5.gif)

## Technologies

- Node.js
- Express.js
- React
- MongoDB
- GraphQL
- Stripe
- Redux

## Website

https://hidden-retreat-43451.herokuapp.com/

## Installation

This program can be run through a browser using the above link to the deployed application. In order to run this program locally, follow the steps below:

1. Clone the repo using `git clone`.
2. Navigate to the root directory of the application in the terminal.
3. Run `npm install` to download all necessary dependancies.
4. Run `npm run seed` to seed data.
5. Run `npm run develop` to compile the application and start the server.
6. Navigate to http://localhost:3000 in your browser to view the application.
7. To stop running the server and exit the application, type `CTRL + C` in the terminal.
