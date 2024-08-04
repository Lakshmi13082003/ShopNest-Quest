

# Shopping Cart Website

A modern web application for managing and purchasing items with a user-friendly shopping cart. This project is built using HTML, CSS, JavaScript, Python with Flask, and MySQL.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Browse products and add them to the shopping cart
- View cart contents and update quantities
- Remove items from the cart
- Checkout process with user input validation
- Secure user authentication and authorization
- Product inventory management

## Technologies

- *Frontend:*
  - HTML
  - CSS
  - JavaScript

- *Backend:*
  - Python with Flask
  - MySQL

- *Other:*
  - Flask-SQLAlchemy (for ORM)
  - Flask-WTF (for forms)
  - Jinja2 (templating engine)

## Installation

### Prerequisites

- Python 3.x
- MySQL Server
- pip (Python package installer)

### Clone the Repository

bash
git clone https://github.com/your-username/your-repository.git
cd your-repository


### Setup Python Environment

1. *Create and activate a virtual environment:*

    bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    

2. *Install required Python packages:*

    bash
    pip install -r requirements.txt
    

### Setup MySQL Database

1. *Create a new MySQL database:*

    sql
    CREATE DATABASE shopping_cart;
    

2. *Import the database schema:*

    bash
    mysql -u your-username -p shopping_cart < schema.sql
    

   Ensure you update the schema.sql file to match your schema if needed.

3. *Update Flask configuration with your database credentials:*

    Open config.py and set the following values:

    python
    SQLALCHEMY_DATABASE_URI = 'mysql+pymysql://username:password@localhost/shopping_cart'
    

## Usage

1. *Run the Flask application:*

    bash
    flask run
    

2. *Open your browser and navigate to:*

    
    http://localhost:5000
    

3. *Explore the application:*
   - Browse and search for products
   - Add items to your cart
   - Manage your cart and proceed to checkout

## Contributing

Contributions are welcome! Please follow these steps:

1. *Fork the repository*
2. *Create a new branch:*

    bash
    git checkout -b feature/your-feature
    

3. *Make your changes*
4. *Commit your changes:*

    bash
    git add .
    git commit -m "Add feature: your-feature"
    

5. *Push to the branch:*

    bash
    git push origin feature/your-feature
    

6. *Create a pull request*

Please ensure your code follows the existing style and passes all tests before submitting a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
