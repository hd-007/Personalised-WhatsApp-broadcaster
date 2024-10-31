# Personalised-WhatsApp-broadcaster
Send personalised Holi, Diwali, Christmas and other festivals messages to your contacts in an automated way

<h1>WhatsApp Message Automation with Selenium</h1>
This Jupyter Notebook automates the process of sending personalized WhatsApp messages to a list of contacts. Leveraging Python and Selenium, the script opens WhatsApp Web, locates each contact, and sends a custom message, making it especially useful for holiday greetings, announcements, or other bulk messaging needs.

<h2>Features</h2>
Automates sending messages to WhatsApp contacts via WhatsApp Web
Allows personalized messages for each contact
Supports running in Google Chrome or Brave browser

<h2>Prerequisites</h2>
Python 3.x: Ensure Python is installed.
Jupyter Notebook: This script runs within a Jupyter Notebook environment.
Selenium: Used to interact with WhatsApp Web.
ChromeDriver or Brave Browser Driver: Required for Selenium to control the web browser.

<h2>Installation</h2>
<h3>Clone the repository:</h3>

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

<h3>Install required packages:</h3>

pip install selenium pandas webdriver-manager

<h3>Download ChromeDriver:</h3>

Make sure your ChromeDriver matches your Chrome/Brave browser version. Download it here.
Place the chromedriver executable in your working directory or specify its path in the Notebook.

<h2>Usage</h2>
<h3>Prepare Contacts File:</h3>

Create a contacts.csv file with the following structure:

Name,Phone

John,+911234567890

Jane,+919876543210


<h3>Run the Notebook:</h3>

Open the Notebook in Jupyter:
jupyter notebook WhatsApp_Automation.ipynb

Follow the instructions within the Notebook cells to run the automation.
Note: You will need to scan the WhatsApp Web QR code for authentication.
