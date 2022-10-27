# Contuso Car Site
Node.js Shopping Cart Via Stripe API

# Description
An e-commerce car web app which utilizes Stripe API for transactions and ExpressJS for serverless.  

# Installation
https://nodejs.org/en/
npm install or yarn add (This will install ExpressJS, Stripe, etc)

# Getting Started
1.  Head over to "Stripe.com" and create an account.
2.  Once inside your account, click on Developers on the right side of the site. 
3.  Next to the Developers button you just click, click to switch to Test-Mode.
4.  On the left pane called Developers and click on API keys.
5.  Create the Publishable key & Secret key. Make sure they keys start with pk_test & sk_test.
6.  Copy the keys and paste it in the .env file.
7.  Back in your code editor to start web app, type and enter npm start. 
8.  If browser does not open, head to your browser and type "http://localhost:3000/" in the address bar to see the site.
9.  The site works like any ecommerce site. To test the checkout with Stripe. Add items to the carts. 
10. Click on Purchase.
11. Enter a fake email, for card number 4242 4242 4242 4242, for date any date and for cvc any number. 
12. Click "Pay $". Done! 
