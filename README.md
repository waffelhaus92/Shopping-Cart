# Shopping Cart Application

This repository contains code for a simple shopping cart application. The application simulates fetching products from a database, allowing users to view a list of products, add them to a cart, and proceed to checkout.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Overview

The code consists of React components that display a list of products, manage a shopping cart, and shows a checkout button. It also includes functionality to fetch data from an API endpoint to restock products.

## Setup

To set up the project locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies by running:
npm install http-server 
4. Run the server using `http-server` command in terminal.
5. Open a web browser and visit localhost:8080.
6. Then enter into the terminal, npm run develop to start the strapi server. 
7. Please go to https://strapi.io/ to get the instructions on how to use it. 

## Usage

After setting up the project, you can access the shopping cart application by opening it in a web browser. The application allows you to:

- View a list of products along with their details such as name, cost, and country of origin.
- Add products to a cart.
- Remove products from the cart.
- Proceed to checkout and view the total cost of items in the cart.
- Restock products by providing an API endpoint URL.

## Features

- **Product List**: Displays a list of products fetched from a simulated database.
- **Shopping Cart**: Allows users to add and remove items from the shopping cart.
- **Checkout**: Calculates the total cost of items in the cart and will allows users to proceed to checkout in the future.
- **Restocking**: Fetches data from an API endpoint to restock products in the inventory.

## License

This project is licensed under the [MIT License](LICENSE).
