# Yoga Classes
## About the App
* Frontend : ReactJS
* Backend : Express, NodeJS
* Database : MongoDB
## Features
* Accepts the user data, does basic validations.
* Only people within the age limit of 18-65 can enroll for the monthly classes and they will
be paying the fees on a month on month basis. I.e. an individual will have to pay the fees
every month and he can pay it any time of the month.
* They can enroll any day but they will have to pay for the entire month. The monthly fee is
500/- Rs INR.
* There are a total of 4 batches a day namely 6-7AM, 7-8AM, 8-9AM and 5-6PM. The
participants can choose any batch in a month and can move to any other batch next
month. I.e. participants can shift from one batch to another in different months but in
same month they need to be in same batch.
* Return the response to front-end depending on the payment response from
CompletePayment() function.
* Use of REST-API


## ENVIRONMENT VARIABLE REQUIRED FOR RUNNING THIS APPLICATION LOCALLY
* MONGODB_URI 
* JWT_SECRET
* PORT

## ER DIAGRAM
[ER DIAGRAM]: https://user-images.githubusercontent.com/65064180/207200877-92968c81-e896-4116-abb0-3988624f745e.png

## DEPLOYMENT
* HEROKU: I have done deployment mostly on Heroku but as Heroku is not free now and my GitHub Student Developer
Pack Offer has not started so don't have access to the Heroku platform.

* NETLIFY: It is used for hosting frontend only so I didn't use it.

* RENDER: I tried deploying with this platform as it allows Full stack project deployment for free. Unfortunately, my frontend is not loading but my backend is working fine (I have tested using Postman). So, I have deployed the frontend separately but APIs are not working there.
Also, my Mumbai University Semester-7th exam is going on and it will be up to 19th December so couldn't give much time on it.


## NOTE : 
* I couldn't try optional tasks because of lack of time as my exams are going on currently.

## DEPLOYMENT LINKS :
Backend : https://yoga-xrrk.onrender.com
Frontend : https://yogaclasses.onrender.com/



