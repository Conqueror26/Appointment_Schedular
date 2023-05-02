# Appointment_Schedular

WEBSITE URL:
https://genuine-cendol-d94cbe.netlify.app

This is an Appointment Schedular App created using MERN stack.

# INTRODUCTION:

This website's functionality is to create and schedule appointments .It tells us what appointments are available and it gives us the option to create new appontments.

# SIGNIN:

This is the part of the website where we can create a new user to login into the website. The email and password is stored inside a mongoDB database.The password is encrypted to ensure saftey for the user.

# LOGIN:

This is the part where we can login to the website.After we enter the correct credentials, we are redirected to the events page.The will load for a little bit of time after clicking submit. There is no indicator on this website which shows whether a page is loading or not.

# EVENT PAGE:

This is the page where we can view appointments available . In this page we can create new appointments and it will add on the appointment list.

# LOGOUT:
If we click this we are redirected to the authentication page.

# DESIGN:

->The frontend is done using REACT JS

->The backend is done using Express NodeJS and MONGODB

# Scalability concerns:

This Website is slow when we login with the user.We have to wait somtime before it connects to the database and displays the event page.

# Functionality Tradeof:

->Due to the time constraint i have ommitted a profile page and updating  the contents in it. I had created the schema for updating email and password in the backend but I couldnt implement it on the front end and in the finished product.

->I havent included date and time fields. I take date and time in my website as a string.



