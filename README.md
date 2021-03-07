# Stripe-Payment-Integration-android   

Clone or download sourcocde and connect with your application and you are good to go.
To be able to work with this app   
1. Create new stripe account and get public key and secret key   
* Add public key in android
```
 stripe = new Stripe(
                getApplicationContext(),
                Objects.requireNonNull("pk_test_51ISLoeDrYpYnN0xnqW7bZ0tJKmtxUEdYOhD8AXoO10S9aMSXZ8Hk6e7EXJvKpn476isXZXgdG5R5TAj7aVXceJZo00bIx1MjgM")
        );
```

2. Add Secret keyin server
```
const stripe = require("stripe")("sk_test_xttiSskmyCYN7fZZ2DJqDgbg00NGpPbMWU");
``` 
3. Run the server code by running    
```node index.js```   

4. Build android project and you shoud able to get the output   

5.Output   

![](https://media.giphy.com/media/TGC47ZRjFg5TEBHYDi/giphy.gif)   


Stripe Dashboard   

![](https://github.com/CodingWithTashi/Stripe-Payment-Integration-android/blob/master/app/src/main/res/drawable/td.PNG?raw=true)


