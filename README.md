

# Stripe Payment Flutter

a simple donation app that is used to demonstrate how to use stripe payment gateway in flutter application

## ✅ Important -
the `.env` file is not included , please use your own secret keys by creating a free [**stripe account**](https://dashboard.stripe.com/register)

`.env` file will be like this - 
```.env
STRIPE_PUBLISH_KEY="pk_test_..."  // Replace this with your own key
STRIPE_SECRET_KEY="sk_test_..."   // Replace this with your own key
```

## 📝 Features -
- User select any amount and currency for donation
- Payment mode accepted is only card (either credit or debit)
- Payment intent gets created by the calling the stripe api from the client side
- User get feedback after the transaction complete or fails
