Amazon Price Alert
-----------------
This repository contains a Python script that monitors the price of a specified product on Amazon. If the price drops below a defined threshold (in this case, 500), the script sends an email notification to the user.

Features
-------------
Web Scraping: Uses requests and BeautifulSoup libraries to scrape product data from Amazon.
Email Notification: Sends an email alert when the product price drops below the specified threshold.
Automated Monitoring: Runs in an infinite loop, checking the product price every 3 seconds.

Requirements
----------------
Python 3.x
requests library
beautifulsoup4 library
A Gmail account with an app password for sending emails

Installation
----------------
Clone the repository:

git clone https://github.com/your-username/amazon-price-alert.git
Navigate to the project directory:

cd amazon-price-alert
Install the required Python libraries:

pip install requests beautifulsoup4

Setup
===============
Enable 2-Step Verification on your Google account.
Generate an app password and replace 'your_app_password' in the script with this app password.
Update the recipient email in the send_mail function if necessary.
Usage
Run the script to start monitoring the price:

python amazon_price_alert.py
The script will check the product price every 3 seconds and send an email alert if the price drops below 500.

License
================
This project is licensed under the MIT License.

Acknowledgments
=======================
Inspired by various web scraping and email automation tutorials available online.
