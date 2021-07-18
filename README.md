# Best Buy Frontend

![Node.js CI](https://github.com/varunjha/Best-Buy-Frontend/workflows/Node.js%20CI/badge.svg)
![Lines of code](https://img.shields.io/tokei/lines/github/varunjha/Best-Buy-Frontend?style=flat)
![GitHub repo size](https://img.shields.io/github/repo-size/varunjha/Best-Buy-Frontend)
![Twitter Follow](https://img.shields.io/twitter/follow/varunjha089?style=flat)
![GitHub language count](https://img.shields.io/github/languages/count/varunjha/Best-Buy-Frontend)
![GitHub top language](https://img.shields.io/github/languages/top/varunjha/Best-Buy-Frontend)

This code is the frontend portion of a shopping application for college project.

[comment]: <> (## Screenshots)

[comment]: <> (![App Screenshot]&#40;https://via.placeholder.com/468x300?text=App+Screenshot+Here&#41;)

## Tech Stack

**Client:** `React`

**Server:** `Django Rest-API`

**Database:** `PostgreSQL`


## Installation

```colsole
ubuntu@ip:~$ git clone https://github.com/varunjha/Best-Buy-Frontend.git

ubuntu@ip:~$ npm install

ubuntu@ip:~$ npm start
```

Look at the [Available Scripts](#Available Scripts) section for further details.

## Methods

As we are using **Django Rest-API** to connect between **Frontend** and **Backend**, so several methods which are 
being used as follows:

| Methods | Routes |
|---|---|
| **GET** | **/api/products** |
| **GET** | **/api/products/11** |
| **POST** | **/api/products/create** |
| **PUT** | **/api/products/update/15** |
| **DELETE** | **/api/products/delete/15** |

## Features

- Product
    - 5-Star rating system
    - User can give their feedback

- User Account
    - Authentication
    - Modify Order
    - View Order
    - Create Order
    - Add feedback to product
    - Look for Previous Orders and Re-Order Them

- Admin Account
    - Admin Panel
    - Add Product
    - Update Product Quantity
    - View Orders
    - Send Promotion Message
    - Pin the Feedback

- Shopping Cart

- Search Product

- Payment Integration
    - PayPal
    - Stripe

- Sending **E-Mail**.
    - Confirming Account
    - Order Successful Message
    - Promotion Message

## Command we have used

For **`Front-End`**

```console
ubuntu@ip:~$ node -v
XXX.XX.X

ubuntu@ip:~$ npm -v
X.XX.X

ubuntu@ip:~$ npx create-react-app frontend

ubuntu@ip:~/frontend$ npm install react-router-dom react-router-bootstrap

ubuntu@ip:~/frontend$ npm install axios

ubuntu@ip:~/frontend$ 

ubuntu@ip:~/frontend$ 

ubuntu@ip:~/frontend$ 
```


## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified, and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project, so you have full control over them. All the commands except `eject` will still work, but they will point to the copied scripts, so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However, we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
