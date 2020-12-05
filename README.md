# Farmerly

> Frontend-> React JS

> Backend-> Node JS & Express JS

> Database-> MongoDB

## Installation Process
1. #### Clone the repo using this command
    ```bash
    git clone https://github.com/Vikash-Pareek/Farmerly-MERN_Stack.git
    ```
2. #### Install NPM Packages
    1. Install Back-end Packages :
    ```bash
    cd Farmerly
    npm install
    ```
    2. Install Front-end Packages :
    ```bash
    cd client
    npm install
    ```
3. Go to the config folder at Farmerly/config & create default.json of mongoDB connection, JWT_SECRET, BRAINTREE_MERCHANT_ID, BRAINTREE_PUBLIC_KEY and BRAINTREE_PRIVATE_KEY.

    ```bash
    cd Farmerly
    cd config
    cat >> default.json
    ```
    (Ctrl+c to exit previous command)
    
    ##### Sample code for default.json
    ```json
    {
      "MONGODB_URI": "YOUR_MONGODB_URI",
      "JWT_SECRET": "YOUR_JWT_SECRET",
      "BRAINTREE_MERCHANT_ID": "YOUR_BRAINTREE_MERCHANT_ID",
      "BRAINTREE_PUBLIC_KEY": "YOUR_BRAINTREE_PUBLIC_KEY",
      "BRAINTREE_PRIVATE_KEY": "YOUR_BRAINTREE_PRIVATE_KEY"
    }

    ```
    ##### Instructions:
    1. You can use any random string as JWTSECRET
    2. #### note: add default.json on .gitignore

4. <b>Deploy this project</b> on your local server by using this command :
    ```bash
    Farmerly
    npm run dev
    ```
    #### note: both backend & frontend server will start at once with the above command.

### Website Description:
    1. User can view all equiments
    2. User can view single equipment
    3. User can search equipments and view equiments by Brand and Price Range
    4. User can Add to Cart, Checkout equipments using credit card info
    5. User can register & sign in
    6. Admin can create, edit, update & delete equipments
    7. Admin can create Brands
    8. Admin can view rented equipments
    9. Admin can change the status of a equipment (processing, shipped, delivered, etc.)
