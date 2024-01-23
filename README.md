# Bus  ticket Booking system App
The ticket Booking system is a web-based application that allows users to book Tickets for a bus. It provides a platform where users can easily book a ticket for the bus. The system aims to streamline the process of ticket booking by providing a convenient and efficient  booking system.




**Server:** Node, Express, MongoDB Atlas

**Client:** HTML, CSS ,Javascript,React.js




## Deployment

**Server side:** Render cloud https://tbs-ye6x.onrender.com/

**Client side:** Netlify https://phenomenal-frangollo-b5553e.netlify.app/

## Features 
-  API Validation
-  Signup/Login
-  Users can book a ticket for a bus 
-  complete flow of  a ticket booking system
-  Only available tickets can be booked


###  Run Locally Clone this Project

```

### Runs the project in the development mode

[http://localhost:8080](http://localhost:8080)

### Search bus from Ranchi to Bokaro only


## NPM Packages
<p align = "center">
<img src="https://repository-images.githubusercontent.com/139898859/9617c480-81c2-11ea-94fc-322231ead1f0" alt="bcrypt.png" width="70" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/cors.png?raw=true" alt="cors" width="70" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/download.png?raw=true" alt="dotenv" width="60" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/JWT.png?raw=true" alt="jwt" width="70" height="50"/>
<img src="https://4008838.fs1.hubspotusercontent-na1.net/hubfs/4008838/mogoose-logo.png" alt="mongoose.png" width="70" height="70"/>     
<img src="https://user-images.githubusercontent.com/13700/35731649-652807e8-080e-11e8-88fd-1b2f6d553b2d.png" alt="nodemon.png" width="50" height="50"/>

</p>
   
   
## API Endpoints

  #### User Signup
```javascript
POST  http://localhost:8080/api/auth/register
```
  #### User Login
```javascript
POST  http://localhost:8080/api/auth/login
```
  #### Search list of Buses from one city to another city
```javascript
POST http://localhost:8080/api/bus/search
```
  #### tO fetch Avialbel seat of a bus
```javascript
GET http://localhost:8080/api/bus/search/id
```
  #### To Add the ticket to cart 
```javascript
POST  http://localhost:8080/api/bus/cart/add
```

  #### To get all ticket avaible in cart
```javascript
POST  http://localhost:8080/api/bus/cart
```


  #### book the ticket
```javascript
POST  http://localhost:8080/api/bus/book/id
```

  #### delete ticket from cart 
```javascript
DELETE http://localhost:8080/api/bus/cart/${id}
```

  #### delete ticket from cart 
```javascript
DELETE http://localhost:8080/api/bus/cart/${id}
```
  #### to get all booked ticket
```javascript
POST http://localhost:8080/api/bus/book
```

  #### cancel the booked ticket 
```javascript
DELETE `http://localhost:8080/api/bus/book/${id}
```







```





 
| `Authors` |
| :-------: | 

 
 [@bire210](https://github.com/bire210) 
