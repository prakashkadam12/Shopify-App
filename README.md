# E-commerce Website

### Project Description

This project involves developing a virtual website called 'E-commerce Website,' which provides users with a list of various products available for purchase in the store. For the convenience of online shopping, a shopping cart feature is provided. After selecting the goods, the user can proceed to the order confirmation process. The system is implemented using Python's web framework Django.

## Features

- **Product Listing:** Browse a wide range of products available for purchase.
- **Product Details:** View detailed information about a specific product.
- **Shopping Cart:** Add products to the cart for a convenient shopping experience.
- **Order Confirmation:** Confirm and place orders seamlessly.
- **User Authentication:** Register and log in to manage personal information and orders.
- **Admin Panel:** Manage products, orders, and users through a comprehensive admin interface.

### Technology Stack

- **Backend:** Django
- **Frontend:** HTML, Bootstrap
- **Database:** SQLite (default for Django, can be configured for other databases)
- **Environment:** Python 3.x

### Installation

1. **Clone the repository to your local machine:**
    ```sh
    git clone https://github.com/yourusername/ecommerce-website.git
    ```

1. **Navigate to the project directory:**
    ```sh
    cd ecommerce-website
    ```

1. **Download and install Python:**
    - Download Python from [python.org](https://www.python.org/downloads/) and follow the installation instructions for your operating system.

1. **Install project dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

1. **Apply database migrations:**
    ```sh
    python manage.py migrate
    ```

1. **Create a superuser account for admin access:**
    ```sh
    python manage.py createsuperuser
    ```

1. **Start the development server:**
    ```sh
    python manage.py runserver
    ```

1. **Open the project in your browser:**
    Open your browser and navigate to [`http://localhost:8000`](http://localhost:8000) to view your project.

