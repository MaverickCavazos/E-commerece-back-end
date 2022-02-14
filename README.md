# E-commerce Back End Starter Code

## description

When you go to a store in person you can physically see the product on the self. With this you can tell what color it is, what kind of product it is, what shape it is, and if it is actually there and not out of stock. This is different for a E-commerece store and which is why keep a database that keeps track of critical information on their products is vital. This helps the consumer get details on the product and helps their system keep track of the price and if it is in stock in order to inform the consumer. This application does just that, it organizes products into categories and tags, while the product table itself houses the pricing and the invetory. It also accepts input and deltetions in order to keep the E-commerce database up to date with the newest information on the products!


## Table of Contents

* [Installation](#installation)
* [Usage](#usage)

## Installation

For this program you will have to have a command line in order to initialize the start up of the application as well as insomnia in order to test the functionality.

## Usage

This app is used to take in information for products of a E-commerce store. It takes in all of the information from the user and sorts them into 3 different tables, categories, product, and tags. Using insomnia you can input new information such as new tags, categories, and products and delete all of the same information. You can also update existing information while keeping certain things the same, for example, you can update the price of a product without having to delete it and re-add it. 

In order to accomplish this functionality you will have to first source the database in mysql using the command source db/schema.sql. From their you seed the database using npm run seed. This is were you can finally start up the application in the command line using npm start, then in insomnia you can start to make get, post, put, and delete requests.

Below is a video demonstrating examples of how to use insomnia to make these requests.

[video](https://watch.screencastify.com/v/lk3woTTEN84VeRoD2r5M)