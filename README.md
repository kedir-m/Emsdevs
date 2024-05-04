Telegram Scraper
Welcome to the Telegram Scraper! This tool allows you to scrape members from Telegram groups and add them to your own group.

Installation
Install Python: Download and install Python from here. Make sure to check the option to add Python to your PATH during installation.
For Termux: Install Python version 3.11 or Python 3.12.
For Windows or Linux: Any Python version should work.
Install Requirements: Open a command prompt and navigate to the project directory. Then, install the required packages using the following command:
Copy code
pip install -r requirements.txt
Create API_ID and API_HASH: Visit https://my.telegram.org/auth to generate your API_ID and API_HASH. Paste these credentials into credentials.txt (open with a text editor). Refer to credentials_example.txt for guidance. Ensure to use multiple API's if using multiple accounts (e.g., 10 API's for 100 accounts).
How to Run the App
Launch the App: Open a command prompt and run main.pyc using the following command:
css
Copy code
python main.pyc
For Termux users, run main_termux.pyc instead.
Login: Use the first option to login to your accounts. Multiple accounts are supported.
Scrape Members: Choose a group to scrape members from. The scraped data will be saved into teammember.csv.
Add Members: Add the scraped members to your own group. Once done, you can scrape another group if needed.
Important Notes
Do Not Modify Files: Do not modify the numbers and numbers_backup files. Use the delete function within the app (main.pyc) to remove accounts.
For any support, bug fixes, or feature suggestions, please contact @EmsdevsTgSupport. Stay tuned for more features!
