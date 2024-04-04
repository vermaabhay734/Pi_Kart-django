## Introduction 👋
Hey there! I'm Abhay Verma, a passionate web developer. 
My mission? Crafting pixel-perfect websites that make users go "Wow!" 🌟

- **Name**: Abhay Verma
- **LinkedIn**: [Connect with me](https://www.linkedin.com/in/vermaabhay734/)
- **GitHub**: [Check out my GitHub](https://github.com/vermaabhay734)
- **Portfolio**: [View live](https://vermaabhay734.github.io/abhay/)


# Pi-Kart

Pi-Kart is a web application developed using Python, Django, and PostgreSQL, aimed at providing users with an e-commerce platform similar to traditional online shopping websites. It incorporates features such as user authentication, product management, order tracking, complaint filing, and feedback submission.

## Features

### Authentication System
- Users need to register and login to access the functionalities of the website.
- Password hashing and secure authentication mechanisms are implemented for user security.

### Server-Side Functionalities
- **Product Management**: Admin users can manage product details including addition, deletion, and updating product information.
- **Complaints and Feedback**: Admin users can view and manage complaints and feedback submitted by customers.
- **Order Tracking**: Admin users can update the tracking status of orders to keep customers informed about their purchases.

### Client-Side Functionalities
- **User Cart**: Registered users can add products to their cart while browsing the website.
- **Order Placement**: Registered users can book their orders through the platform.
- **Order Tracking**: Users can track the status of their orders to know when they will receive their purchases.
- **Complaint Filing**: Users can file complaints if they encounter any issues with their orders or the platform.
- **Feedback Submission**: Users can provide feedback to improve the service and user experience.
- **Logout**: Users can securely logout from their accounts when they finish using the platform.

### Payment Integration
- Payment transactions are facilitated through the PayPal gateway to ensure secure and reliable payment processing.

## Project Screenshots

### Authentication

![Login](/pi-kart-screenshot/Authentication/Registration.jpg "Login")
![Email Verification](/pi-kart-screenshot/Authentication/Verification_mail.jpg "Email Verification")
![Verification Link](/pi-kart-screenshot/Authentication/Verification_link.jpg "Verification Link")
![Registration Verified](/pi-kart-screenshot/Authentication/Registration_verified.jpg "Registration Verified")
![Login](/pi-kart-screenshot/Authentication/Sign_in.jpg "Login")
![Change Password](/pi-kart-screenshot/Authentication/Change_Password.jpg "Change Password")


### Pi-Kart

![Homepage](/pi-kart-screenshot/Pi-Kart/HomePage.jpg "Homepage")
![Product Details](/pi-kart-screenshot/Pi-Kart/Producs.jpg "Product")
![Product Details](/pi-kart-screenshot/Pi-Kart/Product_detail.jpg "Product Details")
![Cart](/pi-kart-screenshot/Pi-Kart/cart.jpg "Cart")
![My Order](/pi-kart-screenshot/Pi-Kart/My_order.jpg "My Order")
![Invoice](/pi-kart-screenshot/Pi-Kart/Invoice.jpg "Invoice")


### Payment

![Choose Payment Gateway](/pi-kart-screenshot/Payment/Credit_debit_card.jpg "Choose Payment Gateway")
![Payment Gateway](/pi-kart-screenshot/Payment/Paynow.jpg "Payment Gateway")
![Paypal Payment Gateway](/pi-kart-screenshot/Payment/Paypal_payment.jpg "Paypal Payment Gateway")
![Transaction Confirmation](/pi-kart-screenshot/Payment/Payment_sucessfull.jpg "Transaction Confirmation")
![Transaction Confirmation](/pi-kart-screenshot/Payment/Payment_sucessfull2.jpg "Transaction Confirmation")
![Admin Review](/pi-kart-screenshot/Payment/payment_detail-data-in-admin.jpg "Admin Review")


### Hacker Login Attempt

![Hacker Login Attempt](/pi-kart-screenshot/hacker-login-attempt/hacker-login-attempt.jpg "Hacker Login Attempt")
![HoneyPot](/pi-kart-screenshot/hacker-login-attempt/honeypot.jpg "HoneyPot")


### Admin

![Admin Login](/pi-kart-screenshot/Admin/Django_admin.jpg "Admin Login")
![Admin Dashboard](/pi-kart-screenshot/Admin/Administration.jpg "Admin Dashboard")
![Manage Products](/pi-kart-screenshot/Admin/Admin_product.jpg "Manage Products")
![Manage Products](/pi-kart-screenshot/Admin/all_product_variation.jpg "All Products")
![Manage Products](/pi-kart-screenshot/Admin/Admin_payment.jpg "Payment")
![Manage Products](/pi-kart-screenshot/Admin/Admin_category.jpg "Category")
![Manage Products](/pi-kart-screenshot/Admin/Admin-user_account_info_data.jpg "User Account Info")


### Database

![Database Schema](/pi-kart-screenshot/database/database-.jpg "Database Schema")
![Database Schema](/pi-kart-screenshot/database/database-1.jpg "Database Schema")
![Account Detail](/pi-kart-screenshot/database/database_account_detail.jpg "Account Detail")
![Payment](/pi-kart-screenshot/database/database_payment.jpg "Payment")
![Product](/pi-kart-screenshot/database/database_product.jpg "Product")
![Database_Variation](/pi-kart-screenshot/database/database_variation.jpg "Database_Variation")
![Review_Rating](/pi-kart-screenshot/database/database_reviewrating_data.jpg "Review_Rating")
![HoneyPot Schema](/pi-kart-screenshot/database/database-honeypot_detail.jpg "HoneyPot Schema")


For more screenshots, please refer to the [pi-kart-screenshot](https://github.com/vermaabhay734/Pi_Kart-django/tree/main/pi-kart-screenshot) in the repository.

## Setup Instructions
1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd Pi-Kart`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Set up PostgreSQL database and configure the settings in `settings.py`.
7. Run database migrations: `python manage.py migrate`
8. Create a superuser: `python manage.py createsuperuser`
9. Start the development server: `python manage.py runserver`

## Dependencies
- Python 3.x
- Django
- PostgreSQL
- PayPal SDK (for payment integration)

## Contributors
- **Portfolio**: [Abhay Verma](https://vermaabhay734.github.io/abhay/)


---