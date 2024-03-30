# Secrets Project

## 📃 Overview

🎯 Intro: 
               A secrets project which will show you secrets after Authentication from your Google account.

🎖 Feature: 
  1. You can sign in or log in( if already signed in ) by your google accout.
   2. You can add your secrets and make them private and can be only accessed after Authentication from google.
#

## Technologies Used

- **Frontend**: HTML, CSS, EmbeddedJs, JavaScript
- **Backend**: Node.js, Express.js, PostgreSQL
- **Authentication**: OAuth using Google
- **Database**: PostgreSQL

 ## Authentication with Google
How Authentication with Google works in this project. This include:

1. Registering your project with the Google Developers Console
2. Setting up OAuth 2.0 credentials
3. Integrating the Google Sign-In button into your application(which is included in code)
4. Handling authentication tokens and user sessions

### You can the get the step by step process of Setting up your Google OAuth Credentials here : https://developers.google.com/workspace/guides/create-credentials

#

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/HarsikaKumari/secretsProject.git
   ```

2. Install the dependencies for the frontend:

   ```bash
   cd secretsProject 
   npm install
   ```

4. Set up the environment variables:
   - Create a `.env` file in the directory.
   - Add the following variables to the `.env` file and provide appropriate values:
     ```
     GOOGLE_CLIENT_ID="Your google Client Id"
     GOOGLE_CLIENT_SECRET="Your google Client Secret"
     SESSION_SECRET="Any word as you want"
     PG_USER="postgres"
     PG_HOST="localhost"
     PG_DATABASE="Your database name"
     PG_PASSWORD="Your pg password"
     PG_PORT="5432"
     ```
7. Access the application in your browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create a new issue or submit a pull request.
   
