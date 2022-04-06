# Blanja

This is Backend for Blanja App.


## Built With

- [Node.js]
- [Mysql]
- [Express.js]


## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/4codeBlack
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Start the Application
   ```sh
   npm start
   ```

## Additional

    This project has been deployed on heroku
    > [HEROKU LINK](https://blanja-backend.herokuapp.com/)



## API Endpoint

auth endpint

    POST    auth/login/customer
    POST    auth/login/seller
    POST    auth/register/customer
    POST    auth/register/seller


customer endpoint

    GET     /customer/all-product
    GET     /customer/product/:id
    GET     /customer/profile/:id
    GET     /customer/address/:id
    GET     /customer/product
    GET     /customer/product/category/:category
    PUT     /customer/product/delete/:id
    PUT     /customer/profile/update/:id
    DELETE  /customer/product/delete/:id
    POST    /customer/address/new/:id


seller endpoint

    POST    /seller/:storename/add-product


