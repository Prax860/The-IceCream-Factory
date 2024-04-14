# The-IceCream-Factory
## Welcome to the Ice Cream Factory Website Project! 
 We are delighted to present a secure HTTPS website for an enchanting ice cream shop named The Ice Cream Factory. This website serves as a one-stop destination for customers to explore the shop's enticing menu, find contact information, and discover the various services available at their store.

### Key Features:

Menu Display: Our website offers a delightful browsing experience, showcasing an extensive range of ice cream flavors, tantalizing toppings, and decadent desserts that are sure to satisfy your sweet tooth.
Contact Information: We make it easy for you to find the shop's address, phone number, and email, making it convenient for you to reach out with any inquiries or orders.
Services: Our website highlights the special services offered by the Ice Cream Factory, such as catering for events, custom flavor requests, and more.
Email Notifications: As a registered customer, you will receive exclusive email notifications about:

Discounts: Stay in the loop with updates on exclusive offers, seasonal promotions, and limited-time discounts that are too good to miss.
New Flavors: Be the first to know about exciting new flavor releases and mouth-watering menu additions that will tantalize your taste buds.
Events: Get notified about upcoming events, tastings, or special occasions organized by the Ice Cream Factory, and be a part of the sweetest celebrations in town.
Technologies Used:

Django Framework: Our website is built using the Django web framework, which ensures robust and scalable backend development, providing a seamless user experience.
SQLite Database: Data is stored securely in an SQLite database, ensuring efficient retrieval and management of customer information and orders, while maintaining the highest level of data security.


### Installation Guide
Ice Cream Shop Website Installation Guide

#### System Requirements:

Python (3.8 or higher)
pip (the Python package installer)
Git (version control system)
Dependency Installation Steps:

#### Install Python:

If you haven't already installed Python, download and install the latest version from the official Python website: https://www.python.org/downloads/

#### Install pip:

pip is included with Python 2.7.9+ and Python 3.4+. If you have a recent version of Python installed, you can skip this step. If not, you can install pip by following the instructions here: https://pip.pypa.io/en/stable/installing/

#### Install Git:

If you haven't already installed Git, download and install the latest version from the official Git website: https://git-scm.com/downloads

Platform-specific Instructions:

### Windows:

#### Clone the Repository:

Open a command prompt and navigate to the directory where you want to clone the repository. Then, run the following command:

Edit
Full Screen
Copy code
git clone https://github.com/your-username/ice-cream-shop-website.git
Replace your-username with your GitHub username.

#### Create a Virtual Environment:

Open a command prompt and navigate to the cloned repository directory. Then, run the following command to create a new virtual environment:

Edit
Full Screen
Copy code
python -m venv venv
This will create a new virtual environment named venv.

#### Activate the Virtual Environment:

Open a command prompt and navigate to the cloned repository directory. Then, run the following command to activate the virtual environment:

Edit
Full Screen
Copy code
venv\Scripts\activate
You should see (venv) in your command prompt, indicating that the virtual environment is active.

#### Install Dependencies:

With the virtual environment active, run the following command to install the required dependencies:

Edit
Full Screen
Copy code
pip install -r requirements.txt
macOS/Linux:

#### Clone the Repository:

Open a terminal and navigate to the directory where you want to clone the repository. Then, run the following command:

Edit
Full Screen
Copy code
git clone https://github.com/your-username/ice-cream-shop-website.git
Replace your-username with your GitHub username.

#### Create a Virtual Environment:

Open a terminal and navigate to the cloned repository directory. Then, run the following command to create a new virtual environment:

Edit
Full Screen
Copy code
python3 -m venv venv
This will create a new virtual environment named venv.

#### Activate the Virtual Environment:

Open a terminal and navigate to the cloned repository directory. Then, run the following command to activate the virtual environment:

Edit
Full Screen
Copy code
source venv/bin/activate
You should see (venv) in your terminal prompt, indicating that the virtual environment is active.

#### Install Dependencies:

With the virtual environment active, run the following command to install the required dependencies:

Edit
Full Screen
Copy code
pip install -r requirements.txt

### User Guide
Ice Cream Shop Website User Guide

Running the Website:

Activate the Virtual Environment:

Follow the instructions in the Installation Guide to activate the virtual environment.

Run Migrations:

Before running the website for the first time, you need to run the database migrations. In the terminal, navigate to the cloned repository directory and run the following command:

Edit
Full Screen
Copy code
python manage.py migrate
This will create the necessary database tables.

Create a Superuser:

If you want to access the Django admin site, you need to create a superuser. Run the following command:

Edit
Full Screen
Copy code
python manage.py createsuperuser
Follow the prompts to create a new superuser.

Run the Website:

With the virtual environment active and the database migrations run, you can now run the website. In the terminal, navigate to the cloned repository directory and run the following command:

Edit
Full Screen
Copy code
python manage.py runserver
This will start the Django development server on http://127.0.0.1:8000/.

Accessing the Website:

Open a web browser and navigate to http://127.0.0.1:8000/ to access the Ice Cream Shop website.

Accessing the Django Admin Site:

If you created a superuser, you can access the Django admin site by navigating to http://127.0.0.1:8000/admin/ in a web browser. Log in with your superuser credentials to manage the website.

Note:

The website will only be accessible on your local machine while the development server is running.
To stop the development server, press Ctrl+C in the terminal.
If you make any changes to the website code, you will need to restart the development server for the changes to take effect.
To run the website on a production server, you will need to deploy the code to a web server and configure the settings accordingly. Consult the Django documentation for more information on deploying Django applications.