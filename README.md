# PaymentTracker API Features


#### Feature 1: Login API

- POST API - api/v1/auth/login 
- Request Body
```
{
  "email":"test@gmail.com",
  "password":"pass123"
}
```

- Response
```js
{
"id": 1,
"name:"Rajesh",
"walletBalance":0
}

```


#### Feature 2: Load Money from bank account into Wallet

- POST API - api/v1/wallet
- Request Body
```
{
  "email":"test@gmail.com",
  "amount":1000
}
```


#### Feature 3: Pay order amount using wallet

- POST API - api/v1/payments
- Request Body
```
{
  "email":"test@gmail.com",
  "orderId":123,
  "amount":1000
}
```
