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

## Portfolio Snapshot
![Portfolio Snapshot]()
![Portfolio Snapshot]()
![Portfolio Snapshot]()
![Portfolio Snapshot]()
![Portfolio Snapshot]()


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
- [Your Name/Username]

## License
[Specify the license under which the project is distributed, e.g., MIT License, GNU General Public License, etc.]

---