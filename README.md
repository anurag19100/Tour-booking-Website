
# MERN Stack Tour Booking Website

A fully fledged web application made using MERN Stack to book tour , review tour, rate tour , advanced authentication features and many more .

## Demo
Site is live at https://tour-booking-website.netlify.app/

## Summary of the App

- Fronted using ReactJS
- Backend using ExpressJS
- MongoDB NoSQL Database is used to store User, Tour, Reviews and Bookings Data
- Used Stripe API to process payments(though it is in the test mode :)
- Used jwt to provide authentication to users
- Used bcrypt to encrypt passwords and implemented features to reset passwords by sending a security token via mail
- Manage booking, check tours map, check user's reviews and rating




## Usage/Examples

* User
  - Users can create accounts and buy Tours
  - There are three types of Users - **Admin**, **Lead-Guide**, **Guide** and **User**
  - Users can buy any tour and write a review and give a rating to the Tours, directly at the website after they have taken a tour.
  - Users can maintain and edit their own personal details
  - Users can reset their password in case they forget it 
* Booking
  - Prevent duplicate bookings after user has booked that exact tour, implement favourite tours
* Advanced authentication features
  - Signup, confirm user email, login with refresh token, two-factor authentication
* And More ! There's always room for improvement!



## Tech Stack

* [NodeJS](https://nodejs.org/en/) - JS runtime environment
* [Express](http://expressjs.com/) - The web framework used
* [Mongoose](https://mongoosejs.com/) - Object Data Modelling (ODM) library
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Cloud database service
* [JSON Web Token](https://jwt.io/) - Security token
* [ParcelJS](https://parceljs.org/) - Blazing fast, zero configuration web application bundler
* [Stripe](https://stripe.com/) - Online payment API
* [Postman](https://www.getpostman.com/) - API testing
* [Mailtrap](https://mailtrap.io/) & [Sendgrid](https://sendgrid.com/) - Email delivery platform
* [Heroku](https://www.heroku.com/) - Cloud platform


## Run Locally

Clone the project

```bash
  git clone https://github.com/super1-1star/Tour-booking-Website.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

## Acknowledgement

* Thanks to Jonas Schmedtmann for creating this awesome beautiful website design


## License

[GitHub: super1-1star](https://www.github.com/super1-1star)

