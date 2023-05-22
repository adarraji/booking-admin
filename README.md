# React Booking Admin App


## Built With

* React
* React Router
* React hooks
* Material UI
* React Context


## Running the Application

To run the application

1. Clone this repo
2. Run `npm install`
3. Run `npm start`
<br/>

## Environmental Variables

Add Cloudinary base url `REACT_APP_CLOUDINARY_BASE_URL` in :
* `src\pages\new\New.jsx`
* `src\pages\newHotel\NewHotel.jsx`
* `src\pages\newRoom\NewRoom.jsx`


Example for Cloudinary API endpoint https://api.cloudinary.com/v1_1/cloud_name



Add backend api url in package.json

`"proxy": "http://localhost:8800/api"`