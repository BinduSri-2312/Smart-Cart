# SmartCart – Online Shopping Platform

SmartCart is a web-based e-commerce application built using Flask and MySQL. It provides a convenient shopping experience with product browsing, cart management, address selection, and online payments.

## Features

### User

* User registration and login
* Browse and search products
* View product details
* Add products to cart
* Select products based on budget
* Manage delivery addresses
* Place orders
* Online payment integration
* View order history
* Download invoices
* Manage user profile

### Admin

* Admin login
* Admin dashboard
* Add, edit, and delete products
* Manage product information
* Manage admin profile

## Technologies Used

* Python
* Flask
* MySQL
* HTML5
* CSS3
* Bootstrap 5
* JavaScript
* Razorpay Payment Gateway

## Project Structure

```text
SmartCart/
├── app.py
├── config.py
├── templates/
│   ├── admin/
│   └── user/
├── static/
│   ├── css/
│   ├── images/
│   └── js/
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project folder:

```bash
cd SmartCart
```

3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate it on Windows:

```bash
venv\Scripts\activate
```

5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Configure your MySQL database and environment variables.

7. Run the application:

```bash
python app.py
```

Open `http://127.0.0.1:5000/` in your browser.

## Author

Busanaboina Bindu Sri

## Note

Configure your own database credentials, secret key, email settings, and payment gateway credentials before running the application.
