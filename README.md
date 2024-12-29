This is a simple Cafe web app made using :

        -> Python & Python Flask
        -> HTML + CSS
        -> Javascript 
        -> MySQL 

Three different Roles / Interfaces :

        -> Customer
        -> Staff
        -> Admin (First admin account to be configured through MySQL Server)

Summary of Functions / Features : 

        -> Signup & Login
        -> Order
        -> Feedbacks
        -> Simple Chatbot
        -> Account Management (Customer / Admin)
        -> Adding of new products (Admin & Staff)
        -> Viewing of all orders (Admin & Staff)
        -> Simple Point system

Security Features also Included :

        -> Input Validation (Signup / Login)
        -> ReCaptcha (Signup / Login)
        -> Account Lockout After Multiple Failed Tries (Login)
        -> Password Strength Check (Signup)
        -> Password Hashing (Signup / Login)
        -> Encryption (Payment)
        -> Masking (Payment)
        -> Session Management (Order)
        -> Input Validation (Feedback)
        -> Session Management (Whole web app)
        -> Logging (whole web app)
        -> Role Based Access Control (Whole web app)

Take Note :

        -> Running of the App is on App_Run.py
        -> There are 2 files (App_Config.py & mysql_handler_log.py) connecting to MySQL
        -> Creating first admin account by changing the role from 'user' to 'admin' in the MySQL server under the table user 
