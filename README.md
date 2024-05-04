# Telegram Scraper

Welcome to the Telegram Scraper! This tool allows you to scrape members from Telegram groups and add them to your own group.

## Installation

1. **Install Python**: Download and install Python from [here](https://www.python.org/downloads/). Make sure to check the option to add Python to your PATH during installation for windows.
   - For Termux: Install Python version 3.11 which is the latest version on termux you can install it using `pkg install python`.
   - For Windows or Linux: python version 3.12

2. **Install Requirements**: Open a command prompt and navigate to the project directory. Then, install the required packages using the following command:
   `pip install -r requirements.txt`
3. **Create API_ID and API_HASH**: Visit [https://my.telegram.org/auth](https://my.telegram.org/auth) to generate your API_ID and API_HASH. Paste these credentials into `credentials.txt` (open with a text editor). Refer to `credentials_example.txt` for guidance. Ensure to use multiple API's if using multiple accounts (e.g., 10 API's for 100 accounts).

## How to Run the App

1. **Launch the App**: Open a command prompt and run `python3.12 main.pyc` using the following command:

   For Termux users, run `python main_termux.pyc` instead.

2. **Login**: Use the first option to login to your accounts. Multiple accounts are supported.

3. **Scrape Members**: Choose a group to scrape members from. The scraped data will be saved into `teammember.csv`.

4. **Add Members**: Add the scraped members to your own group. Once done, you can scrape another group if needed.

## Important Notes

- **Do Not Modify Files**: Do not modify the `numbers` and `numbers_backup` files. Use the delete function within the app (`main.pyc`) to remove accounts.

For any support, bug fixes, or feature suggestions, please contact [@EmsdevsTgSupport](https://t.me/EmsdevsTgSupport). Stay tuned for more features!

---

More features will be added soon. Thank you for using the Telegram Scraper!
