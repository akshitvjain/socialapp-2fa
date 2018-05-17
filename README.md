# socialapp-2fa
A social networking service that implements best practices for performing two-factor authentication. 

The web application was primarily built to incorporate two-factor authentication, and all parts of it are restricted and require a second factor for authentication.
The web app is built using the MEAN stack (MongoDB, Express.js, AngularJS, and Node.js), and to generate a OTP (second factor), the application generates a QR code when the user tries to register and login into the application. Users can retrieve the OTP by scanning the QR code with authenticator apps like Duo, or Google Authenticator. 

