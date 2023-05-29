# React Booking Admin Dashboard

React Admin Dashboard. The app has different pages with data tables for users, hotels and rooms, signle user, signle hotel, single room. You can select, view, delete, sort and filter items in theses tables. You can view a signle item in table by clicking on view button.

You can see the website [here](https://react-booking-admin.netlify.app/)

This is one of three parts of full stack Booking app. You can find the Node.js/MongoDB REST API backend [here](https://github.com/adarraji/booking-node-api) and the React Booking Web application [here](https://github.com/adarraji/booking-react)



To run the application

1. Clone this repo
2. Run `npm install`
3. Run `npm start


## Built With

* HTML
* CSS
* Javascript
* React
* Material-UI
* React Router
* React Context
* React hooks
* Custom hooks


## Environmental Variables

Add Cloudinary base url `REACT_APP_CLOUDINARY_BASE_URL` in :
* `src\pages\new\New.jsx`
* `src\pages\newHotel\NewHotel.jsx`
* `src\pages\newRoom\NewRoom.jsx`


Example for Cloudinary API endpoint https://api.cloudinary.com/v1_1/cloud_name


Replace `process.env.REACT_APP_BACKEND_BASE_URL` with the backend api base url in:

* `src\components\datatable\Datatable.jsx`
* `src\hooks\useFetch.js`
* `src\pages\login\Login.jsx`
* `src\pages\new\New.jsx`
* `src\pages\newHotel\NewHotel.jsx`
* `src\pages\newRoom\NewRoom.jsx`


Example: `http://localhost:8800/api`


## Deployment

Deployed on [Netlify](https://netlify.com)
You can see the website [here](https://react-booking-admin.netlify.app/)


## Authors

- **Ali Darraji** - [https://github.com/adarraji](https://github.com/adarraji)


## Deploy status
[![Netlify Status](https://api.netlify.com/api/v1/badges/8d760479-08e8-4e3c-9463-0d5129f2f718/deploy-status)](https://app.netlify.com/sites/react-booking-12/deploys)

## Screenshots