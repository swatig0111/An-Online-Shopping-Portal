# An-Online-Shopping-Portal
SportElite is a dynamic online platform for showcasing  and selling sports goods. It offers a robust and user friendly interface for users to browse, purchase sports  products, and stay updated with the latest sports gear. Customers can track their orders in real-time, gaining visibility into the delivery process. The search engine provides an easy and convenient way to search for products where a user can Search for a product interactively and the search engine would refine the products available based on the user’s input. The application also provides a drag and drop feature so that a user can add a product to the shopping cart by dragging the item in to the shopping cart. As the super user, the Administrator has total authority over every action that may be taken. Additionally, the list of possible product categories is managed by the administrator, the guestbook entries can be viewed and removed by the administrator.

### Features
- **User Registration & Authentication**: Secure sign-up, login, and logout functionalities.
- **Product Browsing**: Explore a wide range of sports goods with detailed descriptions.
- **Shopping Cart**: Add products to your cart and proceed to checkout with payment option.
- **Order Management**: Track your orders and also view your purchase history.
- **Search Functionality**: Quickly find products by name or category.
- **Responsive Design**: Optimized for both desktop and mobile devices.

### Tech Stack 
1. **Django Framework**:
   - Django: A high-level Python web framework that encourages rapid development and clean, pragmatic design. Django provides a robust set of tools for building web applications, including an ORM (Object
     Relational Mapping), admin interface, authentication, and routing.
     
2. **Frontend Technologies**:
   - HTML5: Used for structuring and presenting content on the web.
   - CSS3: Employed to style the website, including layout, design, and responsiveness.
   - JavaScript: Utilized for creating interactive and dynamic user experiences.
   - Bootstrap: A popular CSS framework that helps in designing responsive and mobile-first websites.
   - jQuery: A fast, small, and feature-rich JavaScript library that simplifies event handling, animation, and AJAX interactions.
     
3. **Backend Technologies**:
   - Python: The primary programming language used for writing Django applications.
     
4. **Database**:
   - By default, Django uses SQLite as the database engine, which is a lightweight, file-based database system.

5. **Template Engine**:
   - Django Templates: Django's built-in template engine used for generating dynamic HTML pages.

6. **Version Control**:
   - Git: A distributed version control system used for tracking changes in the source code. 

### Prerequisites

Requirements for the software and other tools to build, test and push 
- Visual Studio Code(https://code.visualstudio.com/)
- Git(https://git-scm.com/downloads)
  
### Installing

Follow these steps to set up the project:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/swatig0111/An-Online-Shopping-Portal
    cd SportElite
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply Migrations**:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Create a Superuser**:
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the Development Server**:
    ```bash
    python manage.py runserver
    ```

### Usage 
- Visit the home page to browse the latest sports products.
- Sign up for an account to start purchasing.
- Use the shopping cart to manage your selections.
- Checkout when you’re ready to complete your purchase.
- Admins can manage products, categories, and orders through the Django admin interface.

### Screenshots 
1. Home Page :
   
