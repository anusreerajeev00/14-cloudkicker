# CloudKicker Deployment (Task 14)

Public IP: 54.227.103.29

The Flask application is deployed on an AWS EC2 instance and accessed through Nginx reverse proxy.

Flask is running internally on:
127.0.0.1:5000

Nginx is configured on:
Port 80

Important Note:
The root URL (http://54.227.103.29/) shows a 404 error because no route is defined for "/".

The application can be accessed using:
http://54.227.103.29/register
or
http://54.227.103.29/login

After registration, the user is redirected to the login page, and after login, the dashboard is displayed successfully.

Flask is not exposed publicly. Only Nginx handles external requests, making the setup more secure.
