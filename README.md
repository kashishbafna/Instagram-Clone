React-Instagram-Clone
A reactive Single-Page Instagram-Clone built using the MERN stack!
# Requirements

Node.js 

MySQL

PHPMyAdmin

GraphicsMagick (for image processing)

# Features 
User Authentication
Follow System
Post Creation
Likes
Comments
Feed


# Technologies Used
Front-End
React.js
HTML5
CSS3

Backend
Node.js
MySQL
Express.js
PHPMyAdmin
GraphicsMagick

# Usage
1. Fork the repo and then clone it or download it.

2. First install all dependencies:
    ```bash
    # with npm
    npm install
    
    # or with yarn
    yarn
    ```

3. Open PHPMyAdmin, create a DB & import `db.sql` file.
4. Create a `.env` file and insert the following code. 

    ```javascript
    PORT=YOUR_PORT
    SESSION_SECRET_LETTER="anything-secret"
    MYSQL_HOST="host"
    MYSQL_USER="user"
    MYSQL_PASSWORD="password"
    MYSQL_DATABASE="db"
    MAIL="your-email-for-sending email-verification-link"
    MAIL_PASSWORD="password-for-email"
    GOOGLE_GEOLOCATION_KEY='google-geolocation-key'
    ADMIN_PASSWORD='password-for-admin'
    ```
    
5. Expose Environment Variables to Frontend, run
    ```bash
    yarn env
    ```

6. Start the server
    ```javascript
    npm start [OR] yarn start
    ```

7. Now run the app
    ```javascript
    localhost:[PORT] (PORT=defined in .env)
    ```
