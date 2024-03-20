# AIRNET-AIRLINE ✈️


☘️AIRNET AIRLINE  , A flight booking service made on microservices architecture☘️

## Flights And Search Service [🔗](https://github.com/Abhishekbotx/FlightsandSearchService.git)
  
  * Airport Crud
  * City Crud
  * Airplane Crud
  * Flight Crud
    

## Auth Service [🔗](https://github.com](https://github.com/Abhishekbotx/Auth_Service.git))

* SignUp:
  - Allows users to register for an account by providing necessary information such as email and password.

* LogIn:
  - Authenticates users by verifying their credentials (email and password) against stored records in the database.

* Forget Password:
  - Provides functionality for users to request a password reset if they have forgotten their password. Sends a reset link to the user's registered email address.

* Password Change:
  - Allows authenticated users to change their passwords securely by providing their current password and a new password.

* Authentication & Authorization:
  - Implements authentication mechanisms to verify the identity of users and authorization mechanisms to grant or restrict access to certain resources based on user roles and permissions.

* AddEmployee and DeleteEmployee (If user is admin):
  - Provides administrative functionalities to add or remove employees from the system, restricting these operations to users with admin privileges.
    
    
    

## Ticket Booking Service [🔗](https://github.com/Abhishekbotx/Ticket-Booking-Service.git)
  
* Ticket-Booking:
  - Facilitates the booking of flight tickets securely, providing a seamless user experience for purchasing tickets.

* `Razorpay` Integration:
  - Integrates Razorpay payment gateway for secure and reliable online payments, ensuring the safety of financial transactions.
  
* Message Queue Implementation:
  - Implements a message queue to publish the messages of the ticket booking system.
    
    
 
## Reminder Service [🔗](https://github.com/Abhishekbotx/Reminder_Service.git](https://github.com/Abhishekbotx/Auth_Service/tree/master))
  
* `Nodemailer` for Message Service:
  - Implements email reminders using Nodemailer library, allowing users to receive reminders via email.

* `CronJobs` for Message Scheduling:
  - Utilizes CronJobs to schedule and send reminders at specified times, ensuring timely delivery of reminders.

* `RabbitMQ` for Message Queue:
  - Implements a message queue using the RabbitMQ broker and the Amqplib npm library, enabling efficient message handling and processing.
    

    
## API Gateway [🔗](https://github.com/Abhishekbotx/API_GATEWAY)

* Authentication Middleware:
  - Validates authentication tokens for different services to ensure secure communication.

* Proxy Middleware:
  - Utilizes the `http-proxy-middleware` library to proxy requests from the API Gateway to corresponding microservices, abstracting service discovery and routing complexities.

* Rate Limiting and Logging:
  - Utilizes the `Morgan` library for logging HTTP requests and responses, facilitating debugging and monitoring.
  - Implements rate limiting to restrict the number of requests a client can make within a specified time window, enhancing system stability and security.
 

    


