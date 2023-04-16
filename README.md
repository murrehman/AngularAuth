# Employee Management System - In Progress...

Simple webbApp includes:

- Authentication and Authorization (OAuth, AuthGuard)
- Social Media Login feature (Google Login only for now)
- State Mangement (NgXs)
- RestApi

#Instructions

1. Get Google Client Id and put it in environment.ts (frontend)
2. Generate id_rsa_priv.pem on backend using keypair generator.
3. Create .env file with following parameters in backend.

NODE_ENV=development

DB_STRING=mongodb://localhost:12345/AuthDb

DB_STRING_PROD="mongodb db live for production"

GOOGLE_CLIENT_ID=

GOOGLE_CLIENT_SECRET=

GOOGLE_CALLBACK_URL=http://localhost:1234/google/callback



JWT_SECRET_DEV=123

JWT_SECRET_PROD=

4. Run with ng server and node app.js
